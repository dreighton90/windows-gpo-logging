# Windows PowerShell & GPO Logging(Bootcamp)

## 🧠 Executive Summary

This project simulates securing a Windows Server environment by enabling advanced PowerShell logging and configuring Group Policy Objects (GPOs). The goal was to enhance system visibility, enforce account lockout policies, and validate changes using remote Windows virtual machines. These configurations are foundational for detecting malicious activity and supporting compliance in enterprise networks.

---

## ✅ Realism and Business Relevance

- Mirrors real-world tasks performed by Blue Team analysts, system administrators, and compliance teams
- Emphasizes endpoint visibility through script block and module logging
- Supports audit-readiness by enforcing lockout thresholds and security baselines via GPO

---

## 🚀 Scalability Beyond Bootcamp

This lab can be expanded by:
- Forwarding logs to a centralized SIEM like Splunk or Wazuh
- Automating policy deployment using PowerShell scripts
- Creating alert rules based on logged suspicious activity

---

## 🛠️ Tools & Skills Demonstrated

- Group Policy Management Console (GPMC)
- PowerShell logging configuration:
  - Module Logging
  - Script Block Logging
  - Transcription Logging
- Account lockout policy tuning
- Enumerating and reviewing Access Control Lists (ACLs)
- Remote VM configuration and system hardening

---

## 📸 Key Screenshots

- Configuring PowerShell logging via GPMC
- Verifying Group Policy application and Resultant Set of Policy (RSOP)
- Applying account lockout threshold and duration
- Scripted ACL enumeration for visibility into permission sets

---

## 💡 What I Learned

- How to improve detection coverage through native Windows logging
- The role of GPOs in enforcing organization-wide security standards
- How to validate and troubleshoot group policy deployment across systems
- Practical understanding of PowerShell auditing in Active Directory environments

---

## ⚠️ Legal Disclaimer

This project was performed in a fully isolated, virtualized lab environment. No unauthorized access or interaction with production systems occurred. Content is provided strictly for educational and professional development purposes.
