# OSPF adjacency lost

**Type:** Guided simulation. **Jira outcome:** Resolved with Fixed resolution.

## Reported issue

HQ-R1 lost its OSPF adjacency with BR2-R1. The WAN interface remained up/up, Branch 2 could not access HQ applications, and other branches were operating normally.

## Simulated investigation

BR2-R1 was missing from the neighbor table. Comparison showed unique router IDs and area 0 on both sides, but hello/dead timers were 10/40 on HQ-R1 and 30/120 on BR2-R1.

## Proposed correction

Assuming 10/40 is approved, configure BR2-R1's WAN interface with:

```text
ip ospf hello-interval 10
ip ospf dead-interval 40
```

These commands were discussed, not executed on an actual device in this exercise.

## Simulated verification

`show ip ospf neighbor` showed FULL after correction, and a branch user confirmed application access. The results were supplied as exercise findings and documented in Jira.

## Ticketing lesson

Record the mismatch, proposed change, and verification separately. Configuration approval and change procedures must follow the employer's process in a real environment.

