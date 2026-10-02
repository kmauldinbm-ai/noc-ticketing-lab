# NOC Ticketing Lab

Jira Service Management practice by Kenneth Mauldin, connecting CCNA networking concepts with incident documentation, escalation, prioritization, and shift handoffs.

## Scope

These are guided training scenarios, not production incidents. Ticket creation, assignment, status changes, internal notes, resolution selection, and handoff documentation were practiced in Jira. Network alerts, command results, carrier interactions, and user confirmations were supplied as fictional exercise findings. No actual carrier or user was contacted, and no network change was performed for these scenarios.

## Case studies

| Scenario | Workflow practiced | Outcome |
|---|---|---|
| [Branch router unreachable](cases/01-branch-router-unreachable.md) | Investigation notes and recovery documentation | Resolved in Jira |
| [OSPF adjacency lost](cases/02-ospf-timer-mismatch.md) | Configuration comparison and resolution notes | Resolved in Jira |
| [Carrier outage](cases/03-carrier-outage.md) | Escalation, carrier case tracking, recovery verification | Resolved in Jira |
| [Primary WAN failure with working backup](cases/04-backup-link-handoff.md) | Priority assessment and shift handoff | Open with handoff documented |

## Skills practiced

- Creating and assigning tickets; moving work into In Progress, Escalated, and Resolved states.
- Separating reported symptoms, confirmed findings, suspected causes, and planned actions.
- Writing internal investigation and resolution notes.
- Tracking a simulated carrier case and next update time.
- Selecting Medium priority using a simplified training impact guide.
- Documenting open work for the incoming shift.

Three tickets were resolved; the fourth remained open because the primary WAN outage was not restored in the exercise. Adding the missing Fixed resolution option also provided practice with Jira administration.

## Templates

[Incident and handoff template](templates/incident-template.md)

## Next steps

Planned: reproduce a network fault in Packet Tracer or a VM lab and attach actual diagnostic output and recovery evidence to a Jira ticket. That work is not included in the completed scope above.

