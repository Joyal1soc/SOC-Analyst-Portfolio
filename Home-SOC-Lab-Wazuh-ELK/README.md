# 🛡️ Home SOC Lab – Wazuh

**Status: ✅ Completed**

# Home SOC Lab using Wazuh

## Overview

This project demonstrates the deployment of a Home Security Operations Center (SOC) using Wazuh SIEM on Ubuntu with a Windows endpoint for log collection and security monitoring.

## Objectives

- Deploy Wazuh Manager
- Connect Windows Agent
- Collect Security Logs
- Detect authentication events
- Investigate alerts
- Understand MITRE ATT&CK mapping

---

## Architecture

Windows Endpoint
        │
        │ Wazuh Agent
        ▼
Ubuntu Server
(Wazuh Manager)
        │
        ▼
Indexer
        │
        ▼
Dashboard

---

## Environment

- VMware Workstation
- Ubuntu Server
- Windows 10
- Wazuh Manager
- Wazuh Agent

---

## Features

- Centralized log collection
- Authentication monitoring
- Failed login detection
- Rule-based alert generation
- Severity classification
- MITRE ATT&CK mapping

---

## Sample Detection

Generated multiple failed login attempts on Windows and observed alerts on the Wazuh Dashboard.

Investigated:

- Rule ID
- Severity
- Source IP
- Username
- Timestamp

---

## Skills Demonstrated

- SIEM
- Wazuh
- Windows Event Logs
- Linux Administration
- Alert Triage
- Log Analysis
- Incident Investigation
- MITRE ATT&CK

---

## Future Improvements

- Active Response
- File Integrity Monitoring
- Sysmon Integration
- Suricata Integration
