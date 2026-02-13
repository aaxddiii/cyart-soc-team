# Task 5 – Evidence Analysis & Chain of Custody

## Objective
To perform basic digital evidence analysis, identify suspicious activity, and document evidence while maintaining forensic integrity and chain-of-custody principles.


## Environment Used
- Ubuntu SOC Lab VM
- Native Linux forensic utilities
- Elastic Stack (for correlation reference)
- No direct Windows VM was used due to resource constraints


## Evidence Context
As part of a suspected security incident, network activity on the SOC workstation was analyzed to identify abnormal or suspicious connections. Live system evidence was collected carefully to avoid data alteration.


## Step-by-Step Workflow

### Step 1: Evidence Identification
Network connections were identified as relevant evidence to determine:
- Active services
- Unexpected outbound connections
- Local service exposure


### Step 2: Evidence Collection
The following command was executed:

bash
ss -tunap
