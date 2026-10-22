🛡️ Advanced-Hunting
Advanced Threat Hunting & Detection Engineering using Kusto Query Language (KQL)
📖 Overview

This repository contains a curated collection of Kusto Query Language (KQL) queries developed for use with Microsoft Defender XDR Advanced Hunting, Microsoft Sentinel, and related security monitoring platforms.

The queries are designed to support:

🔍 Proactive Threat Hunting
🚨 Incident Investigation
🧠 Detection Engineering
🛠️ Security Operations Center (SOC) Activities
📊 Security Analytics & Visibility

The primary objective of this repository is to help identify, investigate, and respond to advanced threats, including emerging attack techniques, exploitation attempts, and suspicious behaviors that may bypass traditional signature-based security controls.

🎯 Detection Focus Areas

This repository includes detection rules and hunting queries related to:

💥 Zero-Day Exploitation & Emerging Threat Detection
🌐 Vulnerable Internet-Facing Applications & PHP Exploitation
🦠 Malware, Ransomware & Post-Exploitation Activity
🕵️ Living-off-the-Land (LotL) Techniques
🐚 Web Server Exploitation & Suspicious Shell Spawning
🔐 Persistence, Privilege Escalation & Lateral Movement
⚡ Suspicious PowerShell, Script & Command Execution
🛡️ Microsoft Defender Tampering & Security Control Evasion
👤 Abnormal Identity, Endpoint & Process Activity
🚫 Defense Evasion & Anti-Forensics Techniques
📉 Security Hygiene, Vulnerability Exposure & Misconfiguration Detection
🧪 Included Detection Scenarios

Current detection examples include:

Detection Name	Description
🔵 BlueHammer Detection	Detects indicators and behaviors associated with BlueHammer activity.
🔴 RedSun Detection	Hunting queries for RedSun-related attack patterns.
🔴 RoguePlanet Detection	CVE-2026-50656 / RoguePlanet hunting query.
🌐 PHP Vulnerability & Shell-Spawning Hunt	Identifies potentially vulnerable PHP versions on internet-facing devices and hunts for suspicious shell processes launched by web-server or PHP-related processes.
🖥️ Devices Missing Weekly Full AV Scan	Identifies endpoints that missed scheduled antivirus full scans.
⚠️ Suspicious Process Execution	Detects abnormal or high-risk process behaviors.
📜 Abnormal PowerShell Activity	Identifies encoded, obfuscated, or suspicious PowerShell usage.
🔑 Persistence Mechanism Detection	Detects registry, startup, and scheduled-task persistence methods.
🧬 Endpoint Anomaly Hunting	Queries for unusual endpoint behaviors and anomalies.
Note: Detection coverage depends on available telemetry, query logic, product configuration, and the environment being monitored. Hunting results require investigation and should not automatically be treated as confirmation of compromise.
🎯 Repository Goals

The purpose of this repository is to:

✅ Provide reusable and adaptable hunting queries
🧠 Support SOC analysts, DFIR teams, and threat hunters
📈 Improve detection coverage across Microsoft security platforms
⚡ Accelerate investigation and response workflows
🔬 Share practical detection engineering techniques
🔄 Continuously evolve detections against emerging threats and attacker tradecraft
🧰 Technologies & Platforms
🛡️ Microsoft Defender XDR Advanced Hunting
☁️ Microsoft Sentinel
📘 Kusto Query Language (KQL)
🚀 Usage

Queries can be used or adapted within supported environments, including:

Microsoft Defender XDR Advanced Hunting
Microsoft Sentinel Logs and analytics workflows
Microsoft Defender XDR custom detection rules, where the query meets the platform's requirements
Scheduled analytics rules in Microsoft Sentinel
Threat hunting and incident investigation workflows

Before deploying a query as a scheduled or custom detection rule, validate its schema compatibility, execution requirements, performance, and alerting behavior in your environment.

Queries may need to be modified to account for differences in data sources, table schemas, retention periods, permissions, and security configurations.

🤝 Contribution & Improvements

This repository will continue to expand with:

➕ New detection scenarios and threat hunts
⚙️ Query optimization and performance improvements
🧩 MITRE ATT&CK technique mappings
🧠 Advanced threat hunting methodologies
📚 Practical detection engineering use cases
🔍 Investigation guidance and false-positive tuning

Contributions, improvements, and new detection ideas are welcome.

📌 Disclaimer

These queries are provided for defensive security research, threat hunting, incident investigation, and detection engineering purposes only.

They are shared as starting points for security analysis and are not guaranteed to detect every variant of a threat or attack technique.

Always validate and test queries against your environment before using them in production. Review detection results, tune for false positives, and confirm that required telemetry is available before enabling automated alerts or response actions.