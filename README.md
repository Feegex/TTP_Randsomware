# TTP_Randsomware
Objective: Contain and eradicate ransomware to minimize damage and restore services.
Trigger: Detection of file encryption or ransom note on systems.
Steps:
Detection and Triage

MITRE ATT&CK Mapping:
Tactic: Impact
Technique: T1486 (Data Encrypted for Impact)
Details: Identify ransomware variant and infected endpoints.
Tools: Malware detection (e.g., Bitdefender, Microsoft Defender).
Containment

MITRE ATT&CK Mapping:
Tactic: Containment
Technique: Isolate Network Segments
Details: Disconnect affected systems from the network to limit spread.
Tools: Firewall rules, EDR containment options.
Investigation

MITRE ATT&CK Mapping:
Tactic: Execution
Technique: T1203 (Exploitation for Client Execution)
Details:
Identify initial entry vector.
Trace ransomware activity (e.g., lateral movement, privilege escalation).
Tools: Forensic tools (e.g., Autopsy), log analyzers.
Eradication

MITRE ATT&CK Mapping:
Tactic: Defense Evasion
Technique: T1070 (Indicator Removal on Host)
Details:
Remove malware and associated persistence mechanisms.
Apply patches and update antivirus signatures.
Tools: Malware removal tools (e.g., Malwarebytes).
Recovery

MITRE ATT&CK Mapping:
Tactic: Recovery
Technique: T1490 (Inhibit System Recovery)
Details:
Restore from known-good backups.
Monitor for reinfection attempts.
Tools: Backup tools (e.g., Veeam, Acronis).
Post-Incident Activities

MITRE ATT&CK Mapping:
Tactic: Impact
Technique: Document Lessons Learned
Details: Conduct a retrospective analysis to identify weaknesses and improve response.
Tools: Knowledge management tools (e.g., Confluence).
