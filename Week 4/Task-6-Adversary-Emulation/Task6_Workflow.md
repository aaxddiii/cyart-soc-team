# Task 6 – Adversary Emulation Practice

## Objective
To simulate adversary behavior at a conceptual and detection-validation level using MITRE ATT&CK techniques, and evaluate SOC detection
readiness without executing live attacks.


## Why Full Caldera Was Not Used
MITRE Caldera requires:
- Dedicated agent endpoints
- Significant system resources
- Network reachability between attacker and victim

Given system constraints, adversary emulation was performed using:
- MITRE ATT&CK technique mapping
- Simulated attack artifacts
- Detection logic validation in Elastic and TheHive


## Emulation Approach Used
- Technique-based emulation (not payload-based)
- Focus on detection capability and response readiness
- Validation against SOC telemetry and workflows
