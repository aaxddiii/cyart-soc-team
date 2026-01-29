Attack Simulation:
A VSFTPD backdoor exploit was simulated on a vulnerable VM using Metasploit.

Detection:
Wazuh generated an alert for unauthorized service access.

| Time | Source IP | Alert | MITRE |
|----|-----------|------|-------|
| 11:00 | 192.168.1.100 | VSFTPD Exploit | T1190 |

Response:
The affected VM was isolated and the attacker IP was blocked.

Conclusion:
This exercise demonstrated the complete SOC workflow from
detection to response and documentation.
