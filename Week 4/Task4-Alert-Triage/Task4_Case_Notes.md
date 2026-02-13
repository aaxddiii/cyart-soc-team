# Task 4 – Case Notes (SOC Analyst)

## Case Title
Suspicious Phishing File Hash


## Initial Observation
A file hash was identified during review of a suspected phishing-related activity. The source of the indicator was manual review, simulating alert intake from an email security tool.


## Investigation Performed
- The indicator was added as an observable in TheHive
- External threat intelligence validation was performed using AlienVault OTX
- The hash returned multiple pulses indicating prior malicious usage


## Assessment
Based on threat intelligence correlation, the indicator is considered malicious. No evidence of execution or lateral movement was observed in the lab environment.


## Conclusion
This case represents a validated phishing-related indicator. The incident was documented for tracking and reporting purposes. Preventive controls such as email filtering and user awareness remain critical.


## Analyst Notes
This investigation highlights the importance of external threat intelligence when internal telemetry is limited.
