# Core SOC Concepts

## Cybersecurity Foundations
- **CIA Triad:** Confidentiality, Integrity, Availability
- **SOC vs NOC:** SOC focuses on security; NOC ensures uptime.

## Frameworks
- **NIST CSF**
- **MITRE ATT&CK**
- **ISO 27001**

## SOC Process Flow
Detection → Investigation → Response → Recovery

### Example
Using MITRE ATT&CK to map an attacker’s persistence technique helps analysts determine next steps in incident handling.

---

## 2.1 Understanding the SOC Mission

The mission of a Security Operations Center (SOC) is to **protect an organization’s digital assets** by continuously monitoring, detecting, and responding to cybersecurity threats. This involves maintaining **situational awareness** and being prepared to react to incidents effectively to minimize damage.

---

## 2.2 Key SOC Functions

A SOC performs several critical functions:

- **Monitoring:** Constantly watching network traffic, logs, and systems for suspicious activity.
- **Detection:** Identifying potential security threats using tools and analytics.
- **Investigation:** Analyzing alerts to verify and understand incidents.
- **Response:** Containing and mitigating confirmed security incidents.
- **Recovery:** Restoring affected systems to normal operation.
- **Reporting:** Documenting incidents and SOC activities for stakeholders and compliance.

---

## 2.3 Security Monitoring Tools

### 2.3.1 SIEM (Security Information and Event Management)

- Collects and aggregates logs from across the IT environment.
- Correlates events to detect suspicious behavior.
- Generates alerts for security analysts to investigate.

### 2.3.2 EDR (Endpoint Detection and Response)

- Provides visibility into endpoint activities.
- Detects and responds to malicious behavior on devices.
- Often integrates with SIEM for enhanced detection.

### 2.3.3 IDS/IPS (Intrusion Detection and Prevention Systems)

- Monitors network traffic for known attack signatures or anomalies.
- IDS alerts security teams; IPS can automatically block malicious traffic.

### 2.3.4 Threat Intelligence Platforms (TIPs)

- Aggregates data from external sources about emerging threats.
- Helps SOC teams stay informed and prepare defenses.

---

## 2.4 Incident Lifecycle in a SOC

Understanding the phases of an incident helps the SOC team manage threats effectively:

1. **Preparation:** Policies, tools, and training are established.
2. **Identification:** Detection of a potential incident.
3. **Containment:** Limiting the scope and impact of the incident.
4. **Eradication:** Removing the threat from the environment.
5. **Recovery:** Restoring and validating system integrity.
6. **Lessons Learned:** Reviewing the incident to improve defenses and processes.

---

## 2.5 SOC Team Roles and Responsibilities (Brief Overview)

| Role              | Primary Responsibilities                         |
|-------------------|-------------------------------------------------|
| SOC Manager       | Oversees operations and resource allocation     |
| SOC Analyst (L1)  | Initial triage and alert validation              |
| SOC Analyst (L2)  | In-depth investigation and analysis              |
| SOC Analyst (L3)  | Advanced threat hunting and forensics            |
| Incident Responder| Manages containment, eradication, and recovery  |
| Threat Hunter     | Proactively searches for hidden threats          |

---

## 2.6 Common SOC Metrics and KPIs

Tracking performance is essential to measure SOC effectiveness:

- **Mean Time to Detect (MTTD):** Time taken to detect a threat.
- **Mean Time to Respond (MTTR):** Time taken to respond and mitigate.
- **Number of Incidents Detected**
- **False Positive Rate**
- **Incident Resolution Rate**

---

## 2.7 Challenges in Core SOC Operations

- Alert overload and false positives leading to analyst fatigue.
- Lack of skilled personnel and continuous training needs.
- Integration of disparate security tools and data sources.
- Keeping up with the rapidly evolving threat landscape.
- Maintaining compliance while managing operational efficiency.

---

## 2.8 Emerging Concepts and Technologies

- **Behavioral Analytics:** Detecting threats by unusual behavior patterns.
- **Artificial Intelligence (AI) & Machine Learning (ML):** Automating detection and response.
- **SOAR (Security Orchestration, Automation, and Response):** Streamlining and automating incident handling.
- **Extended Detection and Response (XDR):** Integrating multiple security products for holistic defense.
- **Zero Trust Security:** Assumes breach, verifying every access request continuously.

---

## 2.9 Summary

Core SOC concepts form the foundation for a successful cybersecurity defense strategy. From understanding the SOC mission to mastering the incident lifecycle and leveraging modern tools, these principles guide SOC teams in protecting their organizations efficiently and effectively.

---

## 🧠 Key Terms to Remember

- **SIEM**  
- **EDR**  
- **IDS/IPS**  
- **Incident Lifecycle**  
- **MTTD / MTTR**  
- **SOAR**  
- **XDR**

---

## ✅ Self-Check Questions

1. What are the main functions of a SOC?  
2. Describe the incident lifecycle phases.  
3. What roles are typically found in a SOC team?  
4. Why are MTTD and MTTR important metrics?  
5. Name some emerging technologies impacting SOC operations.  

---
