# 🛡️ Internal Security Audit – Botium Toys

## 1. Project Overview

This project demonstrates an internal IT security audit for Botium Toys, a fictional U.S.-based toy company experiencing rapid digital growth. As part of a cybersecurity portfolio, this audit assesses existing controls, identifies vulnerabilities, and provides actionable remediation aligned with compliance standards.

---

## 2. Scenario Summary

Botium Toys operates from a single physical location, serving as office, store, and warehouse. The company's increasing online presence has raised concerns about their ability to securely scale operations and remain compliant with international regulations (e.g., PCI DSS, GDPR).

To address this, the IT manager initiated an internal audit using the NIST Cybersecurity Framework (CSF). This project involves reviewing assets, identifying risks, and completing a controls and compliance checklist to assess the organization's security posture.

---

## 3. Objectives

- Evaluate the organization’s current security posture
- Identify control gaps and compliance risks
- Recommend improvements aligned with NIST CSF
- Ensure adherence to standards such as PCI DSS, GDPR, and SOC reports

---

## 4. Supporting Documents

The following files are included in this repository:

- 📄 `Botium-Toys-Scope-goals-and-risk-assessment-report.docx` – Initial audit scope and risk summary
- 📄 `Control-categories.docx` – Overview of control domains
- 📄 `Controls-and-compliance-checklist.docx` – Audit checklist completed by the analyst
- 📄 `Internal_Security_Audit_Botium_Toys.docx` – Full report with findings and recommendations

---

## 5. Controls and Compliance Summary

### ✅ Key Controls in Place

- Antivirus software installed and monitored
- Physical locks and CCTV security
- Fire detection/prevention systems
- Privacy policies enforced
- Data integrity verified

### ❌ Control Gaps Identified

- No encryption for customer/payment data
- All employees have unrestricted system access
- No password manager or strong password policy
- No Intrusion Detection System (IDS)
- No formal disaster recovery plan

### 🛠️ Recommendations

1. Enforce **Least Privilege** access model
2. Establish a **Disaster Recovery Plan**
3. Strengthen **Password Policies** and deploy a **Password Manager**
4. Implement **Encryption** for sensitive data
5. Deploy an **Intrusion Detection System (IDS)**
6. Classify and inventory digital assets
7. Apply **Separation of Duties** to critical processes

---

## 6. Compliance Assessment Summary

| Standard | Compliance Gaps |
|---------|------------------|
| **PCI DSS** | No data encryption, all-employee access, weak password practices |
| **GDPR** | No encryption for EU customer data, asset classification missing |
| **SOC 1 & 2** | Least Privilege and data confidentiality controls missing |

---

## 7. Reflection Questions & Answers

### 1. Which control gaps pose the highest risk?

The most critical gaps include:
- **Lack of encryption** for sensitive customer and payment data
- **Universal employee access** to all internal systems (no Least Privilege)
- **Absence of an Intrusion Detection System (IDS)**
- **Missing disaster recovery plans**  
These issues could lead to severe breaches, financial losses, and noncompliance penalties.

---

### 2. How does NIST CSF guide the audit steps?

The NIST Cybersecurity Framework (CSF) provides a clear structure for:
- **Identifying** assets and risks
- **Protecting** systems through appropriate controls
- **Detecting** anomalies (e.g., through IDS)
- **Responding** to incidents (e.g., breach notification)
- **Recovering** operations (e.g., via a disaster recovery plan)  
This audit followed that lifecycle, ensuring a comprehensive security review.

---

### 3. Which compliance fines are most severe for Botium Toys?

**GDPR** penalties are potentially the most severe:
- Up to €20 million or 4% of global annual revenue  
This applies because Botium Toys has **EU customers** and fails to secure their data.

**PCI DSS** violations could also result in:
- Hefty fines from banks/payment processors
- Possible revocation of credit card processing privileges

---

### 4. How would you prioritize remediation efforts?

1. **Implement Encryption** – Secures both payment and personal data  
2. **Enforce Least Privilege & Access Controls** – Limits insider risk  
3. **Deploy an IDS** – Enables real-time threat detection  
4. **Create Disaster Recovery Plans** – Ensures business continuity  
5. **Strengthen Password Policies & Use a Password Manager**  
6. **Classify Assets** – Supports better risk and compliance decisions

---

### 5. How will you measure success post-implementation?

Success can be tracked by:
- **Reduction in audit findings** in follow-up reviews
- **Compliance certifications achieved** (e.g., PCI DSS, GDPR readiness)
- **Fewer security incidents** or breaches over time
- **System logs confirming IDS activity and access restrictions**
- **Positive employee feedback** on usability of new security tools (e.g., password manager)

---

## 8. How to Use This Project

This project can be added to a cybersecurity portfolio or used as an example when preparing for audits, job interviews, or compliance consulting.

📁 To view the full audit report: open `Internal_Security_Audit_Botium_Toys.docx`

---

## 9. License

This project is for educational and professional development use only.
