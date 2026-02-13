# Root Cause Analysis and Lessons Learned – Task 8

## Root Cause Analysis (5 Whys)

| Question                     | Answer                               |  
|------------------------------|--------------------------------------|
| Why did the incident occur?  | User interacted with phishing content|
| Why was phishing successful? | Email filtering missed the threat    |
| Why was filtering weak?      | IOC not previously known             |       
| Why was IOC unknown?         | Threat intelligence update lag       |
| Why was update lag present?  | Manual enrichment workflow           |  


## Lessons Learned
- Threat intelligence automation is critical
- Early detection reduces response complexity
- Documentation improves SOC learning


## Preventive Measures
- Improve email gateway rules
- Automate IOC enrichment
- Conduct regular phishing simulations
