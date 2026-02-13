## 📄 Task5_Evidence_Analysis_Report.md  

# Evidence Analysis Report – Task 5

## Summary
This task involved analyzing live network evidence from a SOC workstation to identify suspicious or unauthorized network activity. Evidence was collected and analyzed without impacting system integrity.

---

## Evidence Collected

| Evidence Type       | Description                         |
|---------------------|-------------------------------------|
| Network Connections | Active TCP/UDP connections using ss |


## Key Observations
- Multiple local services listening on expected ports:
  - Elasticsearch (9200)
  - Kibana (5601)
  - TheHive (9000)
- Encrypted outbound connections to external IPs on port 443
- Docker internal traffic observed between containers


## Assessment
No indicators of malicious activity were identified. All observed connections were consistent with SOC tooling and normal system operations.


## Conclusion
The evidence analysis confirmed that the system was operating within expected parameters at the time of collection. No escalation was required.
