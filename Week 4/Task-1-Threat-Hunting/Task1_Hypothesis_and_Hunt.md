# Threat Hunting Hypothesis – Task 1

## Hypothesis
Unauthorized privilege escalation may be occurring through misuse of valid user accounts.


## Rationale
Credential abuse is a common attack vector and is mapped to:
- MITRE ATT&CK Technique: **T1078 – Valid Accounts**

Attackers often escalate privileges using compromised credentials to maintain persistence and expand access.


## Data Sources
- Authentication and security logs
- Privilege assignment events
- Threat intelligence indicators


## Expected Indicators
- Unexpected admin role assignment
- Privileged actions outside normal working hours
- Accounts performing abnormal actions
