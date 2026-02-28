# Evidence Index 

## A) Attack Simulation (Metasploit + Metasploitable2)
- **Nmap scan of target**  
  - Screenshot: `screenshots/nmap/01-nmap-scan.png`
- **Metasploit module search & selection**  
  - Screenshot: `screenshots/metasploit/01-msf-search-module.png`
- **Exploit executed + session opened**  
  - Screenshot: `screenshots/metasploit/02-session-opened.png`
- **Privilege proof (whoami/id/uname)**  
  - Screenshot: `screenshots/metasploit/03-root-proof.png`

---

## B) Detection & Triage (Elastic + Filebeat)
- **Kibana accessible**  
  - Screenshot: `screenshots/elastic/01-kibana-home.png`
- **Detection event in Discover** (failed SSH login seen in SIEM)  
  - Screenshot: `screenshots/elastic/02-detection-event.png`
  - Reference time: `Feb 27, 2026 @ 11:45:45.000`

---

## C) Response & Containment (CrowdSec)
- **Ban decision applied**  
  - Screenshot: `screenshots/crowdsec/01-ban-command.png`
- **Ban verified via cscli decisions list**  
  - Screenshot: `screenshots/crowdsec/02-decisions-list.png`
  - Reference time: `2026-02-27T11:51:15Z`

---

## D) SOAR / Case Management (TheHive)
- **TheHive running (login or dashboard)**  
  - Screenshot: `screenshots/thehive/01-thehive-ui.png`
- **Case created**  
  - Screenshot: `screenshots/thehive/02-case-created.png`
- **Observable IP added**  
  - Screenshot: `screenshots/thehive/03-observable-ip.png`
- **Tasks added (triage/contain/verify)**  
  - Screenshot: `screenshots/thehive/04-tasks.png`

---

## E) Metrics + RCA + Reporting
- Metrics worksheet: `documentation/05-metrics.md`
- RCA: `documentation/06-rca.md`
- Final report: `documentation/07-final-sans-report.md`
- Executive brief: `documentation/08-executive-brief.md`
