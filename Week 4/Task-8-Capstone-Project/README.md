**Author:** Aaditya Mathur  
**Date Range:** 27–28 Feb 2026  
**Environment:** Ubuntu 24.04 (UTM VM on Mac, ARM64), Metasploitable2 (target VM)  
**Tools:** Nmap, Metasploit, Elastic (Elasticsearch + Kibana), Filebeat, CrowdSec, TheHive


## Objective
Simulate and document a full SOC incident lifecycle:
1. Reconnaissance and attack simulation against a vulnerable target.
2. Centralized logging and detection in SIEM.
3. Incident triage and case management.
4. Response and containment via IP blocking (SOAR-like workflow).
5. Post-incident metrics (MTTD/MTTR/Dwell time), RCA, and reporting.


## Quick Navigation
- Lab setup: `documentation/01-lab-setup.md`
- Attack simulation: `documentation/02-attack-simulation.md`
- Detection and triage: `documentation/03-detection-and-triage.md`
- Containment + SOAR workflow: `documentation/04-containment-and-soar.md`
- Metrics: `documentation/05-metrics.md`
- RCA (5 Whys + Fishbone): `documentation/06-rca.md`
- Final report (SANS-style): `documentation/07-final-sans-report.md`
- Executive briefing: `documentation/08-executive-brief.md`

Evidence:
- Evidence index: `evidence/evidence-index.md`
- Commands + outputs: `evidence/commands-and-outputs.md`
- Screenshots: `screenshots/`


## Summary of What Was Achieved
✅ Nmap enumeration of Metasploitable2 services  
✅ Metasploit exploitation using Samba `usermap_script` module (shell session opened)  
✅ SIEM ingestion (Filebeat → Elastic) and detection of malicious authentication activity  
✅ Containment executed using CrowdSec IP ban  
✅ Incident case created and tracked in TheHive (observables + tasks)  
✅ Metrics calculated (MTTD, MTTR, dwell time)  
✅ RCA completed (5 Whys + Fishbone)  
✅ Final SANS-style report + executive brief prepared


## Notes for Reviewer
- The lab involved two controlled simulations across Feb 27–28:
  - SSH brute-force/detection/containment (Feb 27)
  - Samba exploitation (Metasploit) for adversary emulation (Feb 28)
- Screenshots are organized per tool and referenced in the evidence index.
