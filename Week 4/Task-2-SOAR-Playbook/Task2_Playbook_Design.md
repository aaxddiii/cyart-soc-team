# Phishing Response Playbook – Task 2

## Playbook Name
Automated Phishing Incident Response


## Trigger Condition
- SIEM alert for phishing activity
- Suspicious file hash or IP detected
- User-reported phishing email


## Playbook Steps

### Step 1: Alert Ingestion
- Alert received from SIEM (Elastic / Wazuh-style)
- Severity automatically classified as High


### Step 2: Threat Intelligence Enrichment
- File hash checked against VirusTotal / AlienVault OTX
- IP reputation evaluated


### Step 3: Decision Logic
- If IOC is malicious → proceed to containment
- If IOC is clean → close as false positive


### Step 4: Response Action
- Block IP (CrowdSec logic – conceptual)
- Isolate affected user endpoint (if applicable)


### Step 5: Case Management
- Create incident case in TheHive
- Attach observables and enrichment results


### Step 6: Notification & Closure
- Notify SOC analyst
- Document incident and close case
