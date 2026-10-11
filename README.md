#  Capstone Project: Malware Detection & Response
Attack Monitoring and Analysis
# Malware Detection & Response with Wazuh and VirusTotal

## Objectives
- Reproduce the official Wazuh VirusTotal malware-detection proof of concept in an isolated lab.
- Investigate a newly created file using endpoint monitoring and threat intelligence.
- Demonstrate automated threat removal and remediation verification.

## Goals
- Detect an EICAR test file using Wazuh File Integrity Monitoring (FIM).
- Analyse file hashes and enrich the alert using VirusTotal.
- Determine a verdict based on the investigation evidence.
- Execute and verify Wazuh Active Response.

## Tools Used
- **Wazuh 4.14.7** — Security monitoring, alerting, and response
- **Ubuntu 24.04.5 LTS** — Monitored endpoint
- **VirusTotal** — File reputation and threat intelligence
- **Oracle VirtualBox** — Isolated virtual lab
- **EICAR Test File** — Controlled antivirus detection test artifact

## Outcomes
- Successfully detected the EICAR test file through real-time FIM.
- Correlated file hashes with VirusTotal detection results.
- Triggered automated removal through Wazuh Active Response.
- Verified that the file was removed and the Ubuntu agent remained connected.

## Key Skills
- Threat Intelligence
- File Hash Analysis
- SIEM Investigation
- File Integrity Monitoring (FIM)
- Automated Incident Response
- Remediation Verification
- SOC Reporting
