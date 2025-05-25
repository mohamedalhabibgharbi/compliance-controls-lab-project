# 📋 Controls & Compliance Checklist Assessment

> **Project from Google Cybersecurity Professional Certificate**

This project involves evaluating cybersecurity controls and compliance practices for a fictional company, **Botium Toys**. The assessment identifies gaps and provides actionable recommendations to enhance security and align with industry standards.

---

## 🧪 Exercise Summary

To complete the controls assessment checklist, information from the scope, goals, and risk assessment report was used. Control categories were referenced to understand the type and purpose of each control.

The goal: assess whether Botium Toys has the necessary controls in place.

---

## ✅ Controls Assessment Checklist

| Yes | No  | Control                                         | Explanation |
|-----|-----|--------------------------------------------------|-------------|
|     | X   | **Least Privilege**                             | All employees can access customer data; access should be restricted to reduce breach risk. |
| X   |     | **Disaster Recovery Plans**                     | Not yet implemented. Required to ensure business continuity. |
| X   |     | **Password Policies**                           | Current password requirements are weak, increasing the risk of compromise. |
| X   |     | **Separation of Duties**                        | Currently, the CEO handles payroll and daily ops—this must be separated. |
| X   |     | **Firewall**                                    | A firewall is in place with defined rules. |
|     | X   | **Intrusion Detection System (IDS)**            | Needed to detect potential intrusions. |
|     | X   | **Backups**                                     | Backups are needed to support business continuity during a breach. |
| X   |     | **Antivirus Software**                          | Installed and regularly monitored. |
|     | X   | **Legacy System Maintenance**                   | Legacy systems are monitored but lack a clear maintenance schedule. |
|     | X   | **Encryption**                                  | Not currently used; critical for confidentiality of sensitive info. |
|     | X   | **Password Management System**                  | Not in place; would help with secure and efficient password management. |
| X   |     | **Locks (Physical Security)**                   | Physical locations are secured with locks. |
| X   |     | **CCTV Surveillance**                           | CCTV installed and functioning. |
| X   |     | **Fire Detection/Prevention**                   | Fire alarm and prevention systems are in place. |

---

## 📋 Compliance Checklist

### 🏦 PCI DSS (Payment Card Industry Data Security Standard)

| Yes | No  | Best Practice                                      | Explanation |
|-----|-----|-----------------------------------------------------|-------------|
|     | X   | Only authorized users access credit card info       | All employees currently have access to internal data. |
| X   |     | Process and store credit card info securely         | Credit card data is not encrypted and poorly secured. |
| X   |     | Implement data encryption                           | Encryption is not currently used. |
| X   |     | Adopt secure password policies                      | No password manager or strong policies in place. |

### 🇪🇺 GDPR (General Data Protection Regulation)

| Yes | No  | Best Practice                                      | Explanation |
|-----|-----|-----------------------------------------------------|-------------|
|     | X   | EU customer data is secured                        | Encryption is not in use. |
| X   |     | Data breach notification within 72 hours           | Policy is in place for breach notification. |
|     | X   | Data properly classified and inventoried           | Assets are inventoried, but not classified. |
| X   |     | Privacy policies and procedures enforced           | Policies are enforced among teams. |

### 📊 SOC Type 1 & Type 2 (System and Organization Controls)

| Yes | No  | Best Practice                                      | Explanation |
|-----|-----|-----------------------------------------------------|-------------|
|     | X   | User access policies                                | Least Privilege and Separation of Duties are missing. |
| X   |     | Confidentiality of PII/SPII                         | No encryption to protect PII/SPII. |
| X   |     | Data integrity is maintained                        | Data integrity practices are followed. |
|     | X   | Data access is appropriately limited                | All employees have access, not just those authorized. |

---

## 🛠️ Recommendations

To strengthen Botium Toys’ cybersecurity posture, implement the following:

1. **Least Privilege** – Restrict access to only what employees need.
2. **Disaster Recovery Plans** – Develop and regularly test them.
3. **Password Policies** – Enforce stronger password rules.
4. **Separation of Duties** – Split key roles to prevent fraud.
5. **Intrusion Detection System (IDS)** – Monitor network threats.
6. **Legacy System Management** – Schedule routine maintenance.
7. **Encryption** – Secure sensitive data at rest and in transit.
8. **Password Management System** – Improve password control and reset efficiency.

---

## 🧠 Skills Demonstrated

- Cybersecurity risk assessment
- Controls evaluation
- Compliance benchmarking (PCI DSS, GDPR, SOC)
- Clear documentation & reporting
- Security recommendations

---

## 🧾 About This Project

This work was completed as part of the **Google Cybersecurity Professional Certificate** and demonstrates key cybersecurity competencies such as identifying gaps, analyzing risks, and creating effective recommendations aligned with security frameworks and regulations.

---

## 🙌 Let's Connect

If you're interested in cybersecurity collaboration or feedback, feel free to reach out or explore my other projects!
