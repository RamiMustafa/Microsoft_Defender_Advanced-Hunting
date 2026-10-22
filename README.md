# 🛡️ Advanced-Hunting

> **Advanced Threat Hunting & Detection Engineering using Kusto Query Language (KQL)**

---

## 📖 Overview

This repository contains a curated collection of **Kusto Query Language (KQL)** queries developed for use with **Microsoft Defender XDR Advanced Hunting**, **Microsoft Sentinel**, and related security monitoring platforms.

The queries are designed to support:

* 🔍 Proactive Threat Hunting
* 🚨 Incident Investigation
* 🧠 Detection Engineering
* 🛠️ Security Operations (SOC) Activities
* 📊 Security Analytics & Visibility

The primary objective of this repository is to help identify and investigate advanced threats, including previously unknown attack patterns and zero-day activity that may bypass traditional signature-based security controls.

---

## 🎯 Detection Focus Areas

This repository includes detections and hunting queries related to:

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

---

## 🧪 Included Detection Scenarios

Current detection examples include:

| Detection Name                              | Description                                                          |
| ------------------------------------------- | -------------------------------------------------------------------- |
| 🔵 **BlueHammer Detection**                 | Detects indicators and behaviors associated with BlueHammer activity |
| 🔴 **RedSun Detection**                     | Hunting queries for RedSun-related attack patterns                   |
| 🔴 **RoguePlanet**                          | CVE-2026-50656 / RoguePlanet hunting query                          |
| 🖥️ **Devices Missing Weekly Full AV Scan** | Identifies endpoints that missed scheduled antivirus full scans      |
| ⚠️ **Suspicious Process Execution**         | Detects abnormal or high-risk process behaviors                      |
| 📜 **Abnormal PowerShell Activity**         | Identifies encoded, obfuscated, or suspicious PowerShell usage       |
| 🔑 **Persistence Mechanism Detection**      | Detects registry, startup, and scheduled task persistence methods    |
| 🧬 **Endpoint Anomaly Hunting**             | Queries for unusual endpoint behaviors and anomalies                 |

---

## 🎯 Repository Goals

The purpose of this repository is to:

* ✅ Provide reusable and production-ready hunting queries
* 🧠 Support SOC analysts, DFIR teams, and threat hunters
* 📈 Improve detection coverage across Microsoft security platforms
* ⚡ Accelerate investigation and response workflows
* 🔬 Share practical detection engineering techniques
* 🔄 Continuously evolve against emerging threats and attacker tradecraft

---

## 🧰 Technologies & Platforms

* 🛡️ Microsoft Defender XDR Advanced Hunting
* ☁️ Microsoft Sentinel
* 📘 Kusto Query Language (KQL)

---

## 🚀 Usage

Each query can be executed directly within:

* Microsoft Defender Advanced Hunting Portal
* Microsoft Sentinel Logs & Analytics
* Custom Detection Rules
* Scheduled Analytics Rules
* Threat Hunting Workflows

Queries can also be modified and adapted to fit organizational requirements and detection strategies.

---

## 🤝 Contribution & Improvements

This repository will continue to expand with:

* ➕ New detection scenarios
* ⚙️ Query optimizations
* 🧩 MITRE ATT&CK mappings
* 🧠 Advanced threat hunting techniques
* 📚 Detection engineering use cases

Contributions, improvements, and detection ideas are always welcome.

---

## 📌 Disclaimer

These queries are provided for research, detection engineering, and defensive security purposes only.
Always validate and test detections in your environment before deploying them into production workflows.
