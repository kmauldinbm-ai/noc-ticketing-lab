# Branch router unreachable

**Type:** Guided simulation. **Jira outcome:** Resolved with Fixed resolution.

## Reported issue

BR1-Router was reported unreachable. User impact was initially unconfirmed.

## Simulated findings

Ping to BR1 failed, the upstream router was reachable, and its interface toward BR1 showed down/down. No maintenance was listed. Branch staff reported loss of HQ application access.

Onsite staff subsequently confirmed router power and found a loose WAN cable. Reconnecting the cable returned the interface to up/up.

## Recovery criteria

Successful NOC ping to BR1, branch confirmation of HQ application access, a cleared monitoring alert, and a stable link during verification. These were fictional exercise results, not actual tests.

## Ticketing lesson

Document the cause only after evidence supports it. A failed ping does not alone prove router hardware failure. Record service recovery as well as device reachability before resolving.

