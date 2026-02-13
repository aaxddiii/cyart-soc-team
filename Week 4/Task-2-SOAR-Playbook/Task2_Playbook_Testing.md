# Playbook Testing and Validation – Task 2

## Testing Approach
A simulated phishing alert was used to validate the playbook logic.


## Test Scenario
- Malicious file hash identified
- Hash searched in AlienVault OTX
- Multiple threat pulses detected


## Validation Results

| Playbook Step      | Status    | Notes                         |
|--------------------|-----------|-------------------------------|
| Alert Ingestion    | Success   | Alert received and classified |
| Threat Intel Check | Success   | IOC confirmed malicious       |
| Decision Logic     | Success   | High severity validated       |
| Case Creation      | Success   | TheHive case created          |
| Containment Logic  | Simulated | IP block planned              |
| Documentation      | Success   | Incident recorded             |


## Outcome
The playbook logic successfully handled the phishing scenario from detection to documentation.
