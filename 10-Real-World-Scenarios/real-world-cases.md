# Real-World SOC Scenarios

---

## 10.1 Introduction

Understanding theoretical concepts is essential, but applying them to real-world situations is what truly builds expertise in a Security Operations Center (SOC). This chapter presents practical, realistic SOC scenarios that illustrate common threats, detection strategies, and response actions.

---

## 10.2 Scenario 1: Phishing Attack Detection and Response

### Overview

An employee receives a phishing email containing a malicious link aiming to harvest credentials.

### Detection

- SIEM alerts triggered by unusual login attempts from geographically distant locations.
- Endpoint Detection and Response (EDR) flags execution of suspicious scripts.
- User reports suspicious email via phishing reporting tool.

### Response

- Incident Response team isolates affected endpoint.
- Credentials suspected compromised are reset.
- Email filtering rules updated to block similar messages.
- User education reinforcement through targeted awareness training.

### Lessons Learned

- Importance of multi-layered detection (SIEM + EDR + user reporting).
- Need for rapid containment to prevent lateral movement.
- Continuous user awareness reduces risk exposure.

---

## 10.3 Scenario 2: Insider Threat - Data Exfiltration Attempt

### Overview

A disgruntled employee attempts to copy sensitive files to a USB device and upload data to a personal cloud account.

### Detection

- Data Loss Prevention (DLP) triggers on unusual data transfer volumes.
- Network Access Control (NAC) flags unauthorized device connection.
- UEBA detects anomalous user behavior deviating from baseline activity.

### Response

- Endpoint is quarantined and user account temporarily disabled.
- Forensic analysis conducted to assess data accessed and copied.
- Legal and HR teams engaged for investigation and mitigation.
- Policy review and stricter device control implemented.

### Lessons Learned

- Insider threats require behavioral analytics and endpoint controls.
- Coordination between IT, HR, and legal is critical.
- Policies must be enforced technically and administratively.

---

## 10.4 Scenario 3: Ransomware Infection Containment

### Overview

An endpoint becomes infected with ransomware encrypting critical business files and attempting to propagate.

### Detection

- EDR detects suspicious file encryption processes.
- Network segmentation prevents spread to shared drives.
- SIEM correlates alerts from multiple sources indicating ransomware activity.

### Response

- Immediate containment by isolating the infected device.
- Backup restoration initiated for encrypted files.
- Incident Response team conducts root cause analysis.
- Security patches and system hardening applied to prevent re-infection.

### Lessons Learned

- Automated detection and rapid isolation limit damage.
- Regular backups are essential for recovery.
- Post-incident analysis guides prevention measures.

---

## 10.5 Scenario 4: Web Application Attack

### Overview

Attackers launch a SQL Injection attack against a public-facing web application to access confidential data.

### Detection

- Web Application Firewall (WAF) blocks suspicious HTTP requests.
- SIEM alerts triggered by abnormal query patterns and failed login attempts.
- Logs reviewed for indicators of compromise.

### Response

- Application developers patch the vulnerability.
- WAF rules updated to strengthen protections.
- Incident Response validates no data exfiltration occurred.
- Regular vulnerability assessments scheduled.

### Lessons Learned

- Layered web security controls reduce risk.
- Continuous monitoring and timely patching are critical.
- Collaboration between SOC and development teams enhances security.

---

## 10.6 Summary

Real-world SOC scenarios highlight the importance of **integrated detection technologies, well-coordinated incident response, and continuous improvement**. By studying and practicing these scenarios, SOC teams can enhance their readiness to protect organizations from evolving threats.

---

## 🧠 Key Concepts Applied

- Multi-layered defense strategy  
- Behavioral analytics and anomaly detection  
- Incident containment and eradication  
- Collaboration across teams  
- Continuous learning and improvement  

---

## ✅ Self-Check Questions

1. What are the key indicators for detecting phishing attacks?  
2. How can UEBA help identify insider threats?  
3. What immediate actions should be taken upon ransomware detection?  
4. Why is it important to involve development teams during web application attacks?  
5. How do real-world scenarios improve SOC team effectiveness?  

---
