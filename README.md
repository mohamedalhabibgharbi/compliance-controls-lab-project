# 🎯 Botium Toys – Internal Security Audit  
*A Cybersecurity Portfolio Project (Google Cybersecurity Professional Certificate)*

---

## 1  Activity Overview  

This project demonstrates an **internal security audit** for the fictional company **Botium Toys**.  
You will find:

* The scenario and audit scope  
* Links to supporting documents (`.docx`)  
* My completed **Controls & Compliance Checklist** (tables below)  
* Actionable recommendations based on the findings  

Everything is intentionally kept in this `README.md` so reviewers can grasp the project without downloading separate files. The original Word documents are still available for reference.

---

## 2  Scenario (condensed)

Botium Toys is a growing U.S. toy manufacturer with one physical location (office + storefront + warehouse) and an expanding worldwide e-commerce presence.  
The **IT manager**:

1. Adopted the **NIST Cybersecurity Framework (CSF)**  
2. Defined audit **scope, goals, and assets**  
3. Performed an initial **risk assessment**  

She now requests an **internal IT audit** to:

* Identify gaps in security controls  
* Ensure compliance with PCI-DSS (online payments) and GDPR (EU customers)  
* Estimate potential risks / fines  

My task: **review her materials → complete a Controls & Compliance Checklist → provide recommendations.**

---

## 3  Supporting Materials (Word documents)

| File | Purpose |
|------|---------|
| **[`Botium-Toys-Scope-goals-and-risk-assessment-report.docx`](./Botium-Toys-Scope-goals-and-risk-assessment-report.docx)** | Audit scope, goals, asset list, risk assessment |
| **[`Control-categories.docx`](./Control-categories.docx)** | Definitions & purposes of control categories |
| **[`Controls-and-compliance-checklist.docx`](./Controls-and-compliance-checklist.docx)** | Blank template I completed (see tables below) |
| **[`Internal_Security_Audit_Botium_Toys.docx`](./Internal_Security_Audit_Botium_Toys.docx)** | Narrative write-up of this project |

---

## 4  Controls Assessment Checklist

| Control | In Place? | Explanation |
|---------|:--------:|------------|
| Least Privilege | ❌ | All employees can access customer data; restrict rights to reduce breach risk. |
| Disaster Recovery Plans | ❌ | No DR plans yet; required for business continuity. |
| Password Policies | ❌ | Requirements are weak; easier for attackers to compromise accounts. |
| Separation of Duties | ❌ | CEO handles daily ops *and* payroll – increases fraud risk. |
| Firewall | ✅ | Blocks traffic using defined rules. |
| Intrusion Detection System (IDS) | ❌ | Needed to detect potential intrusions. |
| Backups | ❌ | Critical data backups not in place. |
| Antivirus Software | ✅ | Installed and regularly monitored. |
| Legacy-System Monitoring & Maintenance | ❌ | Legacy assets lack a formal schedule and procedures. |
| Encryption | ❌ | Not used; sensitive data unprotected. |
| Password Management System | ❌ | Would improve secure password storage and resets. |
| Physical Locks | ✅ | Offices / storefront / warehouse adequately locked. |
| CCTV Surveillance | ✅ | CCTV installed and functioning. |
| Fire Detection / Prevention | ✅ | Fire alarms and sprinklers operational. |

---

## 5  Compliance Checklists

### 5.1  PCI DSS – Payment Card Industry Data Security Standard

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| Only authorized users access credit-card data | ❌ | All employees have internal-data access. |
| Credit-card data processed & stored securely | ✅ | But **not encrypted** – see below. |
| Data encryption at all touch-points | ❌ | Encryption not implemented. |
| Secure password management policies | ❌ | Nominal policies; no password manager. |

### 5.2  GDPR – General Data Protection Regulation

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| EU customer data kept private / secured | ❌ | No encryption applied. |
| Breach notification within 72 h | ✅ | Plan exists to notify EU customers. |
| Data classified & inventoried | ❌ | Assets inventoried but not classified. |
| Privacy policies enforced & documented | ✅ | Policies in place across teams. |

### 5.3  SOC 1 & SOC 2 – System and Organization Controls

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| User-access policies established | ❌ | Least Privilege & Separation of Duties missing. |
| Confidentiality of PII / SPII | ❌ | No encryption to protect personal data. |
| Data integrity (complete / accurate) | ✅ | Integrity checks performed. |
| Data available only to authorized users | ❌ | Access open to all employees. |

---

## 6  Recommendations (Top 8)

1. **Implement Least Privilege** – Limit access strictly to job needs.  
2. **Create & test Disaster Recovery Plans** – Ensure continuity.  
3. **Strengthen Password Policies** – Complexity, rotation, MFA.  
4. **Enforce Separation of Duties** – Split critical financial roles.  
5. **Deploy an IDS** – Continuous monitoring for intrusions.  
6. **Schedule Legacy-System Maintenance** – Patch, monitor, document.  
7. **Encrypt Sensitive Data** – At rest and in transit.  
8. **Introduce a Password Manager** – Centralized, secure credential storage.

> **Compliance Focus:** Least Privilege, Separation of Duties, and Encryption are pivotal to closing PCI DSS and GDPR gaps.

---

## 7  Reflection Questions (Answered in `Internal_Security_Audit_Botium_Toys.docx`)

1. Which control gaps pose the highest risk?  
2. How does NIST CSF guide the audit steps?  
3. Which compliance fines are most severe for Botium Toys?  
4. How would you prioritize remediation efforts?  
5. How will you measure success post-implementation?

---

## 8  Skills Demonstrated

* Cybersecurity risk & gap analysis  
* Mapping controls to compliance standards (PCI DSS, GDPR, SOC)  
* Application of **NIST CSF** in a small-business context  
* Written reporting & recommendations  

---

## 9  About the Author

This audit was completed while earning the **Google Cybersecurity Professional Certificate**.  
Feel free to connect if you’d like to discuss security audits or portfolio feedback!

---
