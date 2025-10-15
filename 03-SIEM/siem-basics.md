# SIEM Basics

# Chapter 3: SIEM Basics

---

## 3.1 What is SIEM?

**Security Information and Event Management (SIEM)** is a core technology in modern Security Operations Centers (SOCs). It provides a centralized platform to **collect, analyze, and correlate security data** from across an organization's IT infrastructure in real-time or near real-time.

### Key Functions of SIEM:
- **Log Collection:** Aggregates logs and event data from various sources such as firewalls, servers, applications, endpoints, and network devices.
- **Event Correlation:** Analyzes and links related security events to identify potential threats.
- **Alerting:** Generates alerts based on predefined rules or behavioral anomalies.
- **Dashboards and Reporting:** Provides visualizations and reports for SOC analysts and compliance.
- **Forensics:** Enables detailed investigation of security incidents using historical data.

---

## 3.2 Why SIEM is Important

- Provides **centralized visibility** across complex IT environments.
- Helps detect **advanced threats** that might go unnoticed when analyzing logs individually.
- Supports **incident response** by correlating and prioritizing alerts.
- Assists in **compliance reporting** (e.g., PCI-DSS, HIPAA, GDPR).
- Enables **proactive threat hunting** using historical data.

---

## 3.3 SIEM Architecture Overview

SIEM platforms typically include:

| Component           | Description                                                      |
|---------------------|------------------------------------------------------------------|
| **Data Collection**  | Agents or connectors gather logs from various sources.          |
| **Data Normalization** | Standardizes logs into a common format for analysis.           |
| **Correlation Engine** | Applies rules and analytics to identify suspicious patterns.  |
| **Alerting Module**  | Sends notifications when suspicious activity is detected.       |
| **Dashboard & Reporting** | Provides SOC analysts with visual tools and reports.        |
| **Data Storage**     | Stores logs securely for compliance and forensic analysis.       |

---

## 3.4 Types of Data Collected by SIEM

- **System Logs:** OS events, authentication logs, system errors
- **Network Logs:** Firewall logs, IDS/IPS alerts, traffic flows
- **Application Logs:** Web server logs, database logs, cloud service logs
- **Endpoint Logs:** Antivirus alerts, endpoint protection logs
- **Threat Intelligence Feeds:** External data about known malicious IPs, URLs, and signatures

---

## 3.5 Common SIEM Use Cases

- **Unauthorized Access Detection:** Alerting on failed login attempts or unusual login times.
- **Malware Detection:** Identifying signs of infection from endpoint alerts combined with network traffic.
- **Data Exfiltration Monitoring:** Detecting large or unusual data transfers.
- **Insider Threat Detection:** Spotting suspicious user behavior inside the network.
- **Compliance Auditing:** Tracking access to sensitive data and systems.

---

## 3.6 Challenges with SIEM

- **Data Overload:** High volume of logs can lead to many false positives.
- **Complex Rule Creation:** Requires skilled personnel to create and tune correlation rules.
- **Integration Issues:** Difficulties in collecting logs from all necessary sources.
- **Storage and Performance:** Large data volumes require scalable infrastructure.
- **Alert Fatigue:** Excessive alerts may overwhelm analysts.

---

## 3.7 Best Practices for SIEM Deployment

- Start with **clear objectives** and compliance requirements.
- Use **log management policies** to ensure relevant data is collected.
- Regularly **tune correlation rules** to reduce false positives.
- Implement **incident response workflows** integrated with SIEM alerts.
- Provide **training for SOC analysts** on SIEM use and investigation.
- Consider **automation and SOAR** integration to improve response times.

---

## 3.8 Popular SIEM Solutions

- **Splunk Enterprise Security**
- **IBM QRadar**
- **ArcSight (Micro Focus)**
- **LogRhythm**
- **Microsoft Sentinel (cloud-native SIEM)**
- **Elastic Security (formerly ELK Stack)**

---

## 3.9 Summary

SIEM is a powerful tool that enables SOC teams to gain visibility, detect threats, and respond effectively. Understanding how SIEM works, the types of data it collects, and how to use it optimally is essential for cybersecurity professionals working in or with SOCs.

---

## 🧠 Key Terms to Remember

- **Log Collection**  
- **Event Correlation**  
- **Alerting**  
- **Normalization**  
- **Threat Intelligence**  
- **False Positives**  

---

## ✅ Self-Check Questions

1. What are the core functions of a SIEM system?  
2. Why is data normalization important in SIEM?  
3. Name three types of data sources commonly integrated with SIEM.  
4. What challenges can SIEM implementations face?  
5. How can SIEM alerts be effectively managed in a SOC environment?  

---
