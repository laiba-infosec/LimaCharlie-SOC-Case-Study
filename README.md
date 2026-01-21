
This project demonstrates a Security Operations Center (SOC) workflow using LimaCharlie Endpoint Detection and Response (EDR).

The objective of this project was to monitor endpoint activity, create detection rules, investigate alerts, and document incident response findings.

---

## Tools Used
- LimaCharlie EDR
- Windows Virtual Machine
- VirtualBox / VMware
- GitHub

---

## Project Scope
- Endpoint onboarding
- Telemetry monitoring
- Detection rule creation
- Alert generation
- Incident investigation
- Incident documentation

---

## Detection Scenario
A detection rule was created to monitor command-line activity such as PowerShell execution, which is commonly abused by attackers.

An alert was successfully generated and investigated.

---

## Incident Outcome
The alert was analyzed using process lineage and command-line context.  
The activity was identified as legitimate system behavior (false positive).

---

## Key Learning
- Understanding endpoint telemetry
- SOC alert investigation process
- Importance of false positive analysis
- Detection tuning concepts
