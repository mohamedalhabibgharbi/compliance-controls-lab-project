# 🛡️ Botium Toys – Internal Security Audit  
*A Cybersecurity Portfolio Project (Google Cybersecurity Professional Certificate)*

---

## 1&nbsp;&nbsp;Project Overview  

Botium Toys—a small U.S. toy company with one physical location—has rapidly expanded its e-commerce operations.  
The IT manager launched an **internal audit** (using the NIST Cybersecurity Framework) to discover control gaps, estimate compliance risk, and prioritize remediation.

This repository contains:

| File | Purpose |
|------|---------|
| **`Botium-Toys-Scope-goals-and-risk-assessment-report.docx`** | Audit scope, goals, assets, and initial risk assessment |
| **`Control-categories.docx`** | Reference of security control domains |
| **`Controls-and-compliance-checklist.docx`** | Blank checklist template |
| **`Internal_Security_Audit_Botium_Toys.docx`** | Full narrative of this project (scenario, findings, answers) |

Everything is also reproduced below for quick reading.

---

## 2&nbsp;&nbsp;Scenario (condensed)

> Botium Toys’ online growth pressures the IT team to secure systems, keep business running, and comply with PCI DSS (online payments) and GDPR (EU customers).  
> The manager adopted **NIST CSF**, documented scope/goals/assets, and requested an internal audit to highlight risks and potential fines.

**Your task (completed here):**

1. Review the scope, goals, and risk report.  
2. Fill out a *Controls & Compliance Checklist* (yes/​no + explanations).  
3. Provide recommendations to close the gaps.

---

## 3&nbsp;&nbsp;Controls Assessment Checklist

| Control | In Place? | Explanation |
|---------|:--------:|------------|
| Least Privilege | ❌ | All employees can access customer data; rights must be restricted. |
| Disaster-Recovery Plans | ❌ | None exist; essential for business continuity. |
| Password Policies | ❌ | Very basic; increases risk of compromise. |
| Separation of Duties | ❌ | CEO handles daily ops **and** payroll—fraud risk. |
| Firewall | ✅ | Enforces traffic rules. |
| Intrusion Detection System (IDS) | ❌ | Needed to spot intrusions quickly. |
| Backups | ❌ | Critical data not backed up regularly. |
| Antivirus Software | ✅ | Installed and monitored. |
| Legacy-System Maintenance | ❌ | No formal schedule or procedures. |
| Encryption | ❌ | Not used for sensitive data. |
| Password-Management System | ❌ | Would improve secure credential storage. |
| Physical Locks | ✅ | Office, storefront, and warehouse secured. |
| CCTV Surveillance | ✅ | Cameras installed and functioning. |
| Fire Detection / Prevention | ✅ | Alarms and sprinklers operational. |

---

## 4&nbsp;&nbsp;Compliance Checklist

### 4.1&nbsp;&nbsp;PCI DSS

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| Only authorized users access card data | ❌ | All employees have internal-data access. |
| Credit-card data processed/stored securely | ❌ | Data unencrypted; excessive access rights. |
| Data encryption implemented | ❌ | Encryption not in place. |
| Secure password management policies | ❌ | Weak passwords; no manager deployed. |

### 4.2&nbsp;&nbsp;GDPR

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| EU customer data secured | ❌ | No encryption. |
| Breach notification ≤ 72 h | ✅ | Plan exists. |
| Data classified & inventoried | ❌ | Assets inventoried but not classified. |
| Privacy policies enforced | ✅ | Policies documented and applied. |

### 4.3&nbsp;&nbsp;SOC 1 & SOC 2

| Best Practice | Adhered? | Explanation |
|---------------|:-------:|------------|
| User-access policies established | ❌ | Least Privilege not implemented. |
| PII/SPII confidentiality | ❌ | No encryption safeguards. |
| Data integrity ensured | ✅ | Validation checks in place. |
| Data limited to authorized users | ❌ | Access open to all employees. |

---

## 5&nbsp;&nbsp;Key Recommendations

1. **Implement Encryption** for all sensitive data (PCI & GDPR priority).  
2. **Enforce Least Privilege** and granular access controls.  
3. **Deploy an IDS** for real-time threat detection.  
4. **Create & test Disaster-Recovery Plans**.  
5. **Strengthen Password Policies** and roll out a **Password Manager**.  
6. **Separate Duties** for critical finance & operations tasks.  
7. **Schedule Maintenance** and monitoring for legacy systems.  
8. **Classify Assets** to support risk-based decision-making.

---

## 6&nbsp;&nbsp;Reflection (five audit questions)

1. **Highest-risk gaps:** lack of encryption, unrestricted access, no IDS, no DR plans.  
2. **NIST CSF guidance:** follow Identify → Protect → Detect → Respond → Recover lifecycle.  
3. **Most severe fines:** GDPR (€20 M / 4 % revenue) and PCI DSS (bank penalties & processing loss).  
4. **Remediation priority:**  
   1) Encryption, 2) Least Privilege, 3) IDS, 4) DR plans, 5) Password policy/manager, 6) Asset classification.  
5. **Measuring success:** fewer audit findings, compliance certifications, reduced incidents, verified IDS logs, positive user feedback on new security tools.

---

## 7&nbsp;&nbsp;Using This Project

- **Download** the `.docx` reports for detailed narrative and template versions.  
- **Fork** this repo to practice filling out the checklist yourself.  
- **Share** in your portfolio to showcase audit and compliance skills.

---

## 8&nbsp;&nbsp;License

This repository is provided for educational and professional-portfolio purposes only.
