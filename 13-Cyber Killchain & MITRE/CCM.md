# Cyber Kill Chain vs. MITRE ATT&CK

## 13.1 What is the Cyber Kill Chain?

The **Cyber Kill Chain** is a model developed by Lockheed Martin that outlines the stages of a cyberattack. It is a structured approach to understanding how cyber threats are executed, from the initial reconnaissance phase to the final action on objectives. The model is used by security professionals to detect, prevent, and respond to attacks at each stage of the kill chain.

---

## 13.2 Stages of the Cyber Kill Chain

| **Stage**              | **Description**                                                                 |
|------------------------|---------------------------------------------------------------------------------|
| **Reconnaissance**      | The attacker gathers information about the target, such as IP addresses, domain names, and employee details. |
| **Weaponization**       | The attacker creates a malicious payload and packages it with an exploit. |
| **Delivery**            | The attacker delivers the weaponized payload to the target, typically through email attachments, links, or infected websites. |
| **Exploitation**        | The attacker exploits a vulnerability in the system to execute the malicious code. |
| **Installation**        | The malware is installed on the target system, establishing persistence for further attacks. |
| **Command and Control** | The attacker establishes a command and control (C&C) channel to communicate with the compromised system and issue further commands. |
| **Actions on Objectives** | The attacker carries out the primary goal of the attack, which can include data theft, disruption, or further compromise. |

---

## 13.3 What is the MITRE ATT&CK Framework?

The **MITRE ATT&CK** (Adversarial Tactics, Techniques, and Common Knowledge) is a knowledge base that provides a detailed and structured overview of the tactics and techniques that adversaries use to infiltrate and exploit systems. MITRE ATT&CK helps organizations understand adversary behavior and develop better defense strategies by mapping out attack patterns observed in real-world incidents.

---

## 13.4 Tactics for MITRE ATT&CK

| **Tactic**                | **Description**                                                                   |
|---------------------------|-----------------------------------------------------------------------------------|
| **Reconnaissance**         | Gathering information about the target system to find potential weaknesses. |
| **Resource Development**   | The creation of resources necessary for exploitation, such as setting up infrastructure or gathering malware. |
| **Initial Access**         | Methods used to gain initial access to the target system, such as phishing or exploiting vulnerabilities. |
| **Execution**              | The adversary executes the payload on the target system, often via command execution or exploiting vulnerabilities. |
| **Persistence**            | Techniques used to maintain access to the target system over time, such as installing backdoors. |
| **Privilege Escalation**   | The attacker seeks to increase their level of access to gain control over more resources within the system. |
| **Defense Evasion**        | Methods used to bypass detection, including obfuscation and disabling security features. |
| **Credential Access**      | The attacker attempts to gather user credentials to escalate privileges or move laterally within the network. |
| **Discovery**              | Techniques to gather further information about the system, such as scanning for open ports and services. |
| **Lateral Movement**       | The adversary moves from one compromised system to another to expand their reach within the network. |
| **Collection**             | The gathering of valuable data or information from the target system. |
| **Command and Control**    | Communication between the attacker and the compromised system to issue commands and transfer data. |
| **Exfiltration**          | The process of transferring stolen data from the target system to an external location. |
| **Impact**                 | The final actions carried out by the adversary, such as deleting data, disrupting services, or encrypting files. |

---

## 13.5 Comparison: Cyber Kill Chain vs. MITRE ATT&CK

| **Cyber Kill Chain**              | **MITRE ATT&CK**                                   |
|-----------------------------------|----------------------------------------------------|
| **Reconnaissance**                | **Reconnaissance**: Gathering intelligence on the target. |
| **Weaponization**                 | **Resource Development**: Creating the necessary infrastructure for the attack. |
| **Delivery**                      | **Initial Access**: Gaining access to the target. |
| **Exploitation**                  | **Execution**: Exploiting the vulnerability to execute the attack. |
| **Installation**                  | **Persistence**: Establishing a foothold within the network. |
| **Command and Control**           | **Command and Control**: Establishing communication with the compromised system. |
| **Actions on Objectives**         | **Privilege Escalation, Defense Evasion, Credential Access, Discovery, Lateral Movement, Collection, Exfiltration, Impact**: Achieving the attacker's ultimate goal through various means (e.g., data exfiltration, system disruption). |

---

## 13.6 Key Takeaways

The **Cyber Kill Chain** and **MITRE ATT&CK** frameworks provide complementary models for understanding and defending against cyberattacks. The Cyber Kill Chain focuses on the stages of an attack, while MITRE ATT&CK details the tactics and techniques used at each stage. By mapping real-world attack behaviors to these frameworks, organizations can enhance their cybersecurity posture and proactively detect and respond to attacks at each phase of the kill chain.

---

## 🧠 **Key Terms to Remember**

- Cyber Kill Chain
- MITRE ATT&CK
- Reconnaissance
- Weaponization
- Delivery
- Exploitation
- Installation
- Command and Control
- Actions on Objectives
- Initial Access
- Execution
- Privilege Escalation
- Persistence
- Defense Evasion
- Credential Access
- Discovery
- Lateral Movement
- Exfiltration
- Impact

---

## ✅ **Self-Check Questions**

1. What is the difference between the Cyber Kill Chain and MITRE ATT&CK frameworks?
2. How do the tactics in MITRE ATT&CK help in understanding adversary behavior?
3. Why is it important to map real-world attacks to the Cyber Kill Chain and MITRE ATT&CK?
4. What role does the **Persistence** tactic play in cyberattacks, and how does it compare between the Cyber Kill Chain and MITRE ATT&CK?
5. How can **Exfiltration** be detected in the final stages of an attack?
