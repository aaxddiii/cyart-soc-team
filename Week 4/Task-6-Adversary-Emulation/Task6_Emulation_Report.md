# Adversary Emulation Report – Task 6

This task focused on adversary emulation using MITRE ATT&CK techniques to validate SOC detection capabilities.
Techniques T1566 (Phishing) and T1210 (Exploitation of Remote Services) were selected due to their high prevalence in real-world attacks.

Instead of executing live payloads, technique-based emulation was performed by simulating attacker artifacts such as malicious hashes,
suspicious IPs, and abnormal network behavior. These artifacts were evaluated against existing SOC detection logic in Elastic and
case-handling workflows in TheHive.

The emulation confirmed that alert triage, threat intelligence enrichment, and incident documentation processes were functioning as
expected. Detection gaps were identified at the automation level rather than visibility, providing valuable insight for SOC improvement.
