# SOC Metrics Calculation – Task 7

## Incident Timeline (Mock Phishing Case)

| Event                    | Timestamp |
|--------------------------|-----------|
| Phishing Email Delivered | 10:00     |
| Alert Detected (SIEM)    | 12:00     |
| Analyst Triage Started   | 12:15     |
| Containment Action Taken | 16:00     |
| Incident Closed          | 17:00     |


## Metric Calculations

### Mean Time to Detect (MTTD)
Time from compromise to detection.

**MTTD = 12:00 – 10:00 = 2 hours**


### Mean Time to Respond (MTTR)
Time from detection to containment.

**MTTR = 16:00 – 12:00 = 4 hours**


### Dwell Time
Time attacker remained undetected.

**Dwell Time = 2 hours**


## Interpretation
Lower MTTD indicates strong detection capability, while MTTR reflects response efficiency and automation maturity.
