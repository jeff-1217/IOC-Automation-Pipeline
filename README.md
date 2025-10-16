# IOC Automation Pipeline (n8n + Threat Intelligence Integration)

### 🧠 Purpose
Automates the detection, enrichment, and notification process for suspicious IP addresses (IOCs) in a SOC environment using **n8n** workflows.

### ⚙️ Workflow Overview
1. **Fetch IP Blacklist** → AbuseIPDB API  
2. **Enrich Data** → VirusTotal, AlienVault OTX, Whois  
3. **Aggregate and Tag** → Combine threat data, add tags like “Threat”, “Suspicious”  
4. **Notify Analysts** → Slack and Email alerts (HTML formatted)  
5. **Incident Management** → Auto-create cases in TheHive  
6. **SIEM Update** → Push enriched IOCs to Wazuh Cloud

### 🧩 Tech Stack
- **n8n** (workflow orchestration)
- **AbuseIPDB**, **VirusTotal**, **AlienVault OTX**, **Whois APIs**
- **TheHive**, **Wazuh Cloud**
- **Slack Webhooks**, **Gmail Integration**

### 🚀 Key Advantages
- End-to-end SOC automation  
- Multi-source threat enrichment  
- Real-time alerting and case creation  
- Easy to scale and extend  

### 📈 Outcome
Reduced manual IOC triage effort by ~80%, improved SOC response time, and demonstrated advanced automation and API integration skills.

---

**Author:** [Jefrin Correya](https://www.linkedin.com/in/jefrine07/)  
**Tags:** `#CyberSecurity` `#n8n` `#ThreatIntelligence` `#SOC` `#Automation
