# GoXDR

**KQL Query Library for Microsoft Sentinel and Defender XDR**

A free, open source collection of KQL detection and threat hunting queries, ready to paste and run in Microsoft Sentinel and Defender XDR Advanced Hunting.

Website: https://goxdr.fyi

## What's Inside

* 190+ KQL queries for identity, email, endpoint, cloud, Active Directory and AI security
* Hunt view with filters for category, severity, platform, tables and rule kind (detection or hunt)
* Campaign dossiers that group queries by what an attacker does in sequence
* MITRE page with ATT&CK and ATLAS mapping
* Copy KQL button for instant use in your environment
* Dual platform support: queries are labeled for Sentinel, Defender XDR or both
* Every query lists its SOC action, known false positives and known limitations

## Categories

* AI Security (Agent Governance, Agent Inventory, Supply Chain)
* Identity (Auth Attacks, MFA Attacks, Token Attacks, PIM, B2B Guest, Conditional Access, Device Trust)
* Defender XDR (Endpoint, Azure Activity, Key Vault, Data Exfiltration, Attack Chain, SOC Metrics, Vulnerability Management)
* Email Security (AiTM, BEC, Phishing, Malware, URL Protection, Post-Compromise)
* Active Directory (Privileged Accounts, Attack Tools, Attack Detection, Reconnaissance)
* Workload Identity (Credential Management, Anomaly, Botnet, Geo Anomaly)
* Collaboration Security (Teams, Data Protection)
* OAuth Apps and Consent (Consent, Permissions, App Governance, Threat Detection)
* Non-Interactive Sign-Ins (Token Attacks, Shadow IT, Auth Attacks, Anomaly)
* NTLM and Legacy Auth (Attack Detection, Threat Intel, Compliance, External Access)
* Geolocation (Location, Correlation)

## Usage

1. Open https://goxdr.fyi
2. Search or filter by category, severity, platform or rule kind
3. Click a query to see the description, MITRE mapping and KQL
4. Click Copy KQL and paste it into Advanced Hunting or an Analytics rule

Some queries are hunting queries, not alerts. Read the known false positives before you turn one into a rule.

## Source of Truth

This repository is the official and primary source of [GoXDR](https://goxdr.fyi).

## Contributing

Use the Submit Query and Feedback links on the site, or open an issue in this repository.

## License

This project is licensed under [CC BY 4.0](https://github.com/gokselatakan/GoXDR/blob/main/LICENSE).

Created by [Göksel Atakan](https://www.linkedin.com/in/gokselatakan/)
