# Adversary Technique Mapping – Task 6

## Technique Selected
- **T1566 – Phishing**
- **T1210 – Exploitation of Remote Services**


## Emulated Adversary Behavior

### T1566 – Phishing
Simulated artifacts:
- Suspicious email indicator
- Malicious link / hash observable
- External IP reputation lookup

Expected detections:
- Email security alert
- IOC enrichment via threat intelligence
- Case creation in TheHive


### T1210 – Exploitation of Remote Services
Simulated artifacts:
- Suspicious outbound connection
- Unexpected service exposure
- Abnormal network activity

Expected detections:
- Network alert in SIEM
- Correlation with known exploitation patterns
