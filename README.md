# 🛡️ SoCra Tech – SOC Threat Detection & Incident Response (Apr 2025)

**Analyst:** Onaopemipo David Olugbemiro  
**Role:** SOC Analyst (Threat Detection & Incident Response)  
**Report Type:** SOC Analysis Capstone Project  
**Target Industry:** Technology & Digital Services **(SoCra Tech)**  

---

## 🧠 Project Overview

This project is a **multi-phase SOC analysis and incident response simulation** for **SoCra Tech**, developed as part of my cybersecurity SOC capstone.  
It provides hands-on demonstration of **network traffic capture, firewall implementation, security event monitoring, and incident reporting** using enterprise-grade open-source tools.  

**Key Deliverables:**
- Network traffic analysis with **Wireshark**.  
- Firewall & IDS/IPS enforcement with **pfSense + Snort + pfBlockerNG**.  
- SIEM monitoring & alerting with **Wazuh**.  
- Incident detection report covering brute-force SSH attacks, beaconing anomalies, and vulnerabilities.  
- Final report with **business impact analysis & recommendations**.  

---

## 🛠️ Tools & Technologies

| Tool / Framework | Purpose |
|------------------|---------|
| **Wireshark** | Packet capture & traffic anomaly detection |
| **pfSense** | Firewall & policy enforcement |
| **Snort IDS/IPS** | Intrusion detection & prevention |
| **pfBlockerNG** | GeoIP-based traffic blocking |
| **Wazuh SIEM** | Security monitoring, log correlation, incident response |
| **Kali Linux / Hydra** | Attack simulation & brute-force testing |
| **Ubuntu VM** | Endpoint monitoring (Wazuh agent) |

---

## 🚨 Key Findings

1. **Suspicious Beaconing Activity**  
   - Repeated DNS queries to domains (e.g., `chatling.ai`, `api.10alytics.io`) suggest possible **C2 communication**.  
   - Indicates potential malware presence or automated beaconing.  

2. **Brute-Force SSH Attacks**  
   - Over **5,400 login attempts** detected via Wazuh logs.  
   - Attack patterns included repeated resets & invalid usernames.  

3. **Unencrypted HTTP POST Requests**  
   - Sensitive data observed transmitted over **HTTP instead of HTTPS**.  
   - High likelihood of **data interception risk**.  

4. **High & Critical Vulnerabilities (CVSS > 8.0)**  
   - Multiple high-severity vulnerabilities identified during Wazuh scanning.  
   - Exploitable without remediation.  

---

## 📊 Business Impact

- **Regulatory Risks:** Exposure of sensitive data could lead to **compliance violations** (NDPR/GDPR).  
- **Operational Risks:** Brute-force login attempts and beaconing could enable **unauthorized access & downtime**.  
- **Reputational Risks:** Customer trust could erode due to **perceived weak security controls**.  

---

## 🚀 Recommendations

- Enforce **HTTPS/TLS** across all web traffic.  
- Implement **MFA** for SSH & privileged accounts.  
- Regular **patching & vulnerability management** for CVSS > 7.0.  
- Enable **active response in Wazuh** to auto-block brute-force sources.  
- Apply **network segmentation** to limit lateral movement.  
- Conduct **quarterly user awareness training**.  

---

## ✅ Learning Outcomes

Through this SOC capstone, I gained experience in:  
- **Packet analysis** with Wireshark.  
- **Firewall rule enforcement** & IDS/IPS alerting.  
- **SIEM monitoring** with Wazuh (5,418 brute-force detections).  
- **Incident report writing** for technical & business stakeholders.  
- **Developing actionable recommendations** to strengthen SOC capabilities.  

---

## 🤝 Connect

If you're a recruiter, cybersecurity lead, or SOC professional, feel free to connect with me:

📍 **[LinkedIn](https://www.linkedin.com/in/onaopemipo-olugbemiro-1b377828b/)**  
🐦 **[Twitter](https://x.com/itzonaope)**  
💻 **[GitHub](https://github.com/LyticOnaope)**  

---
