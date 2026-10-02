# Primary WAN failure with backup active

**Type:** Guided simulation. **Jira outcome:** Open, In Progress with handoff note.

## Impact and priority

Branch 4's primary WAN was down. Its backup remained stable, and all 25 users could access HQ applications with slower performance. No critical service was blocked. Medium priority was selected using the exercise's simplified guide; real priorities depend on the organization's impact and urgency matrix.

## Simulated shift handoff

- Current impact: Primary WAN down; backup supports all 25 users with degraded performance.
- Checks completed: Backup stability and HQ application access confirmed in the scenario.
- Carrier case: LAB-4001; no restoration estimate.
- Next action: Continue monitoring; obtain and document the next carrier update at 4:15 PM Central in the exercise.
- If backup fails: Verify connectivity loss, raise to High under the practice guide, and notify the escalation contact and carrier.

The ticket was kept open. No actual incoming technician was notified or assigned during this solo lab.

## Ticketing lesson

A handoff should state impact, findings, external case details, next actions, update deadlines, and escalation triggers. In production, confirm that the incoming shift accepts ownership.

