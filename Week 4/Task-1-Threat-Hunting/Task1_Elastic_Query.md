# Elastic Security Query – Task 1

## Objective
Identify events related to privilege escalation and sensitive role assignments.


## Query Logic
The hunt focused on security events related to elevated privileges.

### Example Query (Conceptual)

event.code: "4672"


## Explanation
Event ID 4672 indicates special privileges assigned to a new logon session, which can signal unauthorized privilege escalation.


## Outcome
Relevant logs were identified and reviewed for:
- User identity
- Timestamp anomalies
- Unexpected role assignments
