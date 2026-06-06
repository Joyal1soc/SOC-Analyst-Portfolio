### 🎯 Objective
Build a fully functional home SIEM environment to practise real Tier 1 SOC analyst workflows — monitoring endpoints, tuning detection rules, and triaging alerts using the MITRE ATT&CK framework.

### 🛠️ Tools Used
- **SIEM:** Wazuh + ELK Stack (Elasticsearch, Logstash, Kibana)
- **Platform:** VMware Workstation Pro
- **Endpoints:** Windows 10 VM + Ubuntu 22.04 VM
- **Attack Simulation:** Kali Linux (Hydra, Nmap)
- **Framework:** MITRE ATT&CK

### 🔧 What I Built
- Deployed Wazuh OVA on VMware — configured Manager, Indexer, and Dashboard
- Connected Windows and Ubuntu endpoints as Wazuh agents
- Simulated real attacks from Kali Linux:
  - SSH brute-force (Hydra)
  - Nmap port scanning
  - Failed login attempts
  - Privilege escalation attempts
- Tuned 15+ custom alert rules for:
  - Brute-force detection (5+ failed logins in 60 seconds)
  - Unauthorized access attempts
  - Privilege escalation
  - File integrity monitoring (/etc/passwd changes)
- Triaged 50+ alerts — classified true positives vs false positives
- Mapped every alert to MITRE ATT&CK techniques
- Built Kibana dashboards for real-time security event visualization

### 📊 Key Findings
- Reduced false positive rate by ~30% through custom rule tuning
- Identified 3 simulated attack chains end-to-end
- Documented SOC runbook for brute-force incident response

### 📸 Key Skills Demonstrated
`Wazuh` `ELK Stack` `SIEM Deployment` `Alert Tuning` `Alert Triage` `MITRE ATT&CK` `False Positive Analysis` `Incident Documentation` `VMware` `Linux`
