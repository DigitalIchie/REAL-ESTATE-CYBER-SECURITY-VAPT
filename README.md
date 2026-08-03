# Corporate Infrastructure Security & VAPT Audit 🚀🛡️

  Project Overview
  Role: Lead Cybersecurity & VAPT Analyst
  Target Sector: Multi-Branch Corporate Real Estate
  Academy Placement Partner: RAD5 Tech Hub
  Core Security Framework Applied: The CIA Triad (Confidentiality, Integrity, Availability)

---

 1. Executive Summary & Problem Statement
The target organization operates a high-value real estate transaction pipeline across three distinct state branches. While the firm possessed advanced physical perimeters (active CCTV networks and strategic law enforcement contact matrices), an internal security assessment revealed a critical cybersecurity vacuum regarding digital asset management, administrative data pipelines, and endpoint session governance. 

This assessment was conducted to migrate the company from a reactive security stance to a proactive model, ensuring the protection of Personally Identifiable Information (PII) of high-net-worth investors and blocking vulnerability vectors for Business Email Compromise (BEC).

---

 2. Comprehensive Threat Reconnaissance Matrix

| Target Asset / Area | Identified Vulnerability | Threat Mechanism & Real-World Impact | Risk Level |
| :--- | :--- | :--- | :--- |
| **IT Desk Workstation** | Active host session left unmonitored for 7 minutes. | Direct path for local data exfiltration, malicious USB injection, or corporate email spoofing by walk-ins. | **🔴 HIGH** |
| **Access Control Gate** | Workstation wakes up from sleep with no re-authentication prompt. | A simple keyboard tap bypasses credential layers, granting full administrative email privileges. | **🔴 HIGH** |
| **Administrative Files** | Historical deeds and receipt tracking managed via manual paper ledger books. | Zero data redundancy. A single localized physical disaster (fire, ink spill) causes total data loss. | **🔴 HIGH** |
| **Workforce Tracking** | Daily staff and visitor attendance recorded in manual paper notebooks. | Open source for internal espionage reconnaissance. Entries are highly prone to physical alteration. | **🔴 HIGH** |
| **Sales Data Pipeline** | Sensitive property deeds and invoices shared via unmanaged personal WhatsApp storage. | High data leakage risk. Departing staff exit the company with proprietary transaction histories on private devices. | **🟡 MEDIUM**
| **Institutional Continuity** | Master system and hosting credentials stored purely in shared memory (IT Officer & CEO). | Severe operational lockout risk during joint human absences or unexpected health emergencies. | **🟢 LOW** |

---

  3. Remediation Architecture & Implemented Solutions

 🔹 Host Endpoint Hardening (Confidentiality & Integrity)
Configured local group policies on the core administrative workstation to enforce an automatic 60-second screen-saver inactivity timeout. Enabled mandatory re-authentication triggers (`Require sign-in on wake up`) to neutralize physical session hijacking vectors.

 🔹 Data Privacy & "Clean-Counter" Protocols (Confidentiality)
Instituted an immediate **Clean-Counter Operational Rule** at the reception terminal. Mandated that all physical logs be closed and contained within locked desk compartments during temporary employee absences to prevent visual data harvesting.

 🔹 Administrative Cloud Migration (Availability)
Designed and structured an access-controlled digital tracking matrix using secure folder directories inside the company's existing Google Drive. This implementation established cloud data redundancy and collapsed employee client-verification lookup latencies from minutes down to a **2-second digital search** (`Ctrl + F`).

 🔹 Data Governance & Link Restrictions (Integrity)
Enforced a strict policy restricting the transmission of raw document media over unmonitored consumer messaging platforms. Transitioned the team to sharing access-controlled, view-only directory links from the secure corporate repository.

 🔹 Disaster Redundancy Registry (Availability)
Established a restricted, multi-factor-authenticated Account Continuity Directory shared exclusively via cloud credentials between executive management and the technical desk to eliminate institutional lockout bottlenecks.

---

 4. Human-Centric Security Defenses (SAT)
To lock in these technical controls, I developed and delivered a **Security Awareness Training (SAT) Briefing** to the corporate staff and administrative heads. The session successfully engineered an alert, **"No-Blame" reporting culture** by training the workforce on:
* Identifying sophisticated real estate phishing trends and urgent wire-transfer scams.
* Executing the 1-second local desktop lock shortkey combination (`Windows Key + L`).
* Safeguarding client data privacy across everyday operational touch points.

---

 5. Commercial Value & Future Implementations
To permanently eliminate the vulnerabilities, physical loss risks, and data alteration loopholes of paper-based logbooks, I architected a technical proposal for a **custom-developed, network-locked, branch-segmented sign-in web application. 

By restricting clock-in access strictly to the company's local network infrastructure, the system will guarantee absolute data integrity and automated multi-branch reporting across all three state offices.

---
Document compiled and pushed by Ernest Uchechukwu Chidi as a core requirement for professional profiling and final graduation tracking at RAD5 Tech Hub.
