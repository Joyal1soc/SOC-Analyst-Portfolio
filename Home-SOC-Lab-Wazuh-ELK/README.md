# 🛡️ Home SOC Lab – Wazuh

**Status: ✅ Completed**

## Overview
Deployed a home SIEM environment using Wazuh on VMware to practise
real Tier 1 SOC analyst workflows — monitoring endpoints, tuning
detection rules, and triaging alerts using the MITRE ATT&CK framework.

## Tools Used
- **SIEM:** Wazuh
- **Platform:** VMware Workstation Pro
- **Endpoints:** Windows + Ubuntu (Linux)
- **Framework:** MITRE ATT&CK

## What I Did

### 1. Deployment
- Deployed Wazuh on VMware Workstation Pro
- Connected Windows and Ubuntu endpoints as Wazuh agents
- Configured log ingestion from both endpoints

### 2. Detection Rule Tuning
Tuned 15+ custom alert rules for:
- Brute-force login attempts
- Unauthorized access attempts  
- Privilege escalation
- Reduced false-positive noise by adjusting alert thresholds

### 3. Alert Triage
- Triaged 50+ security alerts
- Classified each as true positive or false positive
- Mapped every alert to MITRE ATT&CK techniques
- Practised Tier 1 SOC analyst workflows end-to-end

## Alerts Triaged

| Alert | Severity | MITRE Technique | Classification |
|---|---|---|---|
| SSH Brute Force | High | T1110 — Credential Access | True Positive |
| Unauthorized Access Attempt | High | T1078 — Valid Accounts | True Positive |
| Privilege Escalation Attempt | High | T1068 — Exploitation for Privilege Escalation | True Positive |
| Failed Login Spike | Medium | T1110 — Brute Force | True Positive |
| File Integrity Violation | Medium | T1565 — Data Manipulation | True Positive |

## Key Skills Demonstrated
`Wazuh` `SIEM Deployment` `Alert Rule Tuning` `Alert Triage`
`MITRE ATT&CK` `False Positive Analysis` `Incident Documentation`
`VMware` `Ubuntu` `Windows Event Logs`
