# SIEM Basics

## What is SIEM?
Security Information and Event Management (SIEM) collects and correlates logs from multiple systems for real-time threat detection.

## Popular Tools
- Splunk
- IBM QRadar
- Azure Sentinel

## Sample Query (Splunk)
```spl
index=windows sourcetype=WinEventLog:Security EventCode=4625
| stats count by Account_Name, Workstation_Name
| where count > 5
```

## Real-World Use Case
Detecting brute-force login attempts across critical systems and notifying SOC analysts for escalation.
