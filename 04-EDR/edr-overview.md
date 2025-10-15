# Endpoint Detection and Response (EDR)

---

## 4.1 What is EDR?

**Endpoint Detection and Response (EDR)** is a cybersecurity technology focused on continuously monitoring and responding to threats on endpoints such as laptops, desktops, servers, and mobile devices.

### Key Functions of EDR:
- **Continuous Monitoring:** Collects data about endpoint activities in real-time.
- **Threat Detection:** Uses behavioral analysis and threat intelligence to identify suspicious activities.
- **Investigation:** Provides tools to analyze and understand endpoint threats.
- **Response:** Enables rapid containment, remediation, and recovery actions on infected devices.
- **Forensics:** Supports detailed root cause analysis and timeline reconstruction after an incident.

---

## 4.2 Why EDR is Important

- Provides deep visibility into endpoint behavior beyond traditional antivirus.
- Detects advanced threats such as fileless malware, ransomware, and insider threats.
- Enables faster incident response with automated and manual remediation capabilities.
- Helps contain threats at the endpoint before they spread to the network.
- Enhances overall security posture by integrating with SOC workflows and SIEM platforms.

---

## 4.3 EDR Architecture Overview

EDR solutions typically include:

| Component               | Description                                                        |
|-------------------------|--------------------------------------------------------------------|
| **Endpoint Agent**      | Software installed on endpoints that collects telemetry data.     |
| **Data Aggregation Server** | Centralized platform that receives and stores endpoint data.    |
| **Detection Engine**    | Analyzes endpoint data using signatures, heuristics, and behavior analytics. |
| **Alerting Module**     | Generates alerts based on suspicious or malicious activity.       |
| **Response Tools**      | Provides containment options such as isolating endpoints or killing processes. |
| **Forensic Tools**      | Allows investigation of endpoint activity and incident root cause. |

---

## 4.4 Types of Data Collected by EDR

- **Process and Application Activity:** Running processes, executed files, application behaviors.
- **File Activity:** Creation, modification, and deletion of files.
- **Network Connections:** Outbound and inbound connections from the endpoint.
- **User Activity:** Logins, privilege escalations, and command executions.
- **Registry Changes (Windows):** Modifications to system settings.
- **Memory and Disk Artifacts:** Suspicious in-memory activity and artifacts on disk.

---

## 4.5 Common EDR Use Cases

- **Ransomware Detection and Mitigation:** Detecting early signs of ransomware behavior and blocking encryption processes.
- **Malware Detection:** Identifying known and unknown malware through behavior analysis.
- **Insider Threat Monitoring:** Spotting unusual user or process behavior.
- **Threat Hunting:** Enabling analysts to proactively search endpoints for hidden threats.
- **Incident Response:** Rapidly isolating compromised devices to contain outbreaks.

---

## 4.6 Challenges with EDR

- **Data Volume:** Large amounts of telemetry data can overwhelm storage and analysts.
- **False Positives:** Behavioral detection can sometimes trigger benign activities.
- **Complexity:** Requires skilled staff to configure, tune, and investigate alerts.
- **Endpoint Performance Impact:** Agents may consume resources on endpoints.
- **Integration:** Effective use often requires integration with SIEM and SOAR tools.

---

## 4.7 Best Practices for EDR Deployment

- Deploy EDR agents across all critical endpoints.
- Regularly update detection signatures and behavior models.
- Establish clear incident response workflows based on EDR alerts.
- Train SOC analysts on EDR investigation and response capabilities.
- Integrate EDR with SIEM and SOAR for comprehensive monitoring and automation.
- Continuously tune alerts to balance detection sensitivity and noise reduction.

---

## 4.8 Popular EDR Solutions

- **CrowdStrike Falcon**
- **SentinelOne**
- **Microsoft Defender for Endpoint**
- **Carbon Black (VMware)**
- **Sophos Intercept X**
- **CylancePROTECT**

---

## 4.9 Summary

EDR is a vital tool for modern cybersecurity defense, providing in-depth visibility, detection, and rapid response capabilities at the endpoint level. Mastering EDR concepts and operations enhances a SOC team's ability to defend against sophisticated attacks and contain threats before they cause widespread damage.

---

## 🧠 Key Terms to Remember

- **Endpoint Agent**  
- **Telemetry**  
- **Behavioral Analytics**  
- **Containment**  
- **Threat Hunting**  
- **Incident Response**  

---

## ✅ Self-Check Questions

1. What differentiates EDR from traditional antivirus solutions?  
2. What types of data does an EDR agent collect from endpoints?  
3. How does EDR assist in ransomware detection and response?  
4. What are common challenges when deploying EDR solutions?  
5. Why is integration with SIEM and SOAR important for EDR effectiveness?  

---

