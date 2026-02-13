# Task 4 – Alert Triage & Case Management (TheHive)

## Objective
To simulate alert triage and incident documentation using a case management system, and to understand how SOC analysts validate alerts using threat intelligence.


## Environment Used
- Ubuntu VM (SOC Lab)
- TheHive Community Edition (Docker-based)
- AlienVault OTX (External Threat Intelligence)


## Alert Context (Simulated)
A suspicious file hash related to a potential phishing incident was selected as the alert indicator. Due to the absence of live Wazuh alert ingestion, the alert was manually simulated, which reflects how analysts often handle alerts from email reports or third-party tools.


## Step-by-Step Workflow

### Step 1: Access TheHive
- TheHive was accessed via browser at `http://localhost:9000`
- Organization and user context were already configured


### Step 2: Create a New Case
- A new case was created with:
  - **Title:** Suspicious Phishing File Hash
  - **Severity:** Medium
  - **Description:** Suspicious hash identified during phishing investigation

This step represents initial alert intake in a SOC.


### Step 3: Add Observable
- A file hash observable was added to the case
- Hash value was obtained from threat intelligence examples
- Observable type: `hash`

This simulates indicator enrichment during alert triage.


### Step 4: Threat Intelligence Validation
- The hash was manually searched in AlienVault OTX
- OTX returned multiple pulses, confirming the indicator was previously reported as malicious

This step validated the alert and reduced false positives.


### Step 5: Case Documentation
- Findings were documented directly in the case description and notes
- No automated analyzers were used due to Community Edition limitations


## Outcome
The alert was successfully triaged, validated using external intelligence, and documented using SOC case management practices.
