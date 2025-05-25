# 🛡️ Botium Toys – Internal Security Audit  
*A Cybersecurity Portfolio Project (Google Cybersecurity Professional Certificate)*

---

## 1&nbsp;&nbsp;Project Overview  

Botium Toys—a small U.S. toy company with one physical location—has rapidly expanded its e-commerce operations.  
The IT manager launched an **internal audit** (using the NIST Cybersecurity Framework) to discover control gaps, estimate compliance risk, and prioritize remediation.

This repository contains:

| File | Purpose |
|------|---------|
| [**Botium-Toys-Scope-goals-and-risk-assessment-report.docx**](./Botium-Toys-Scope-goals-and-risk-assessment-report.docx) | Audit scope, goals, assets, and initial risk assessment |
| [**Control-categories.docx**](./Control-categories.docx) | Reference of security control domains |
| [**Controls-and-compliance-checklist.docx**](./Controls-and-compliance-checklist.docx) | Blank checklist template |
| [**Internal_Security_Audit_Botium_Toys.docx**](./Internal_Security_Audit_Botium_Toys.docx) | Full narrative of this project |

---

## 2&nbsp;&nbsp;Scenario (condensed)

> Botium Toys’ online growth pressures the IT team to secure systems, keep business running, and comply with PCI DSS (online payments) and GDPR (EU customers).  
> The manager adopted **NIST CSF**, documented scope/goals/assets, and requested an internal audit to highlight risks and potential fines.

**Task completed in this project:**

1. Reviewed scope, goals, and risk report.  
2. Completed a Controls & Compliance Checklist.  
3. Provided recommendations to address control and compliance gaps.

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
| User-access policies established | ❌ | Least privilege not in place. |
| Sensitive data is protected | ❌ | No encryption of PII/SPII. |
| Data integrity maintained | ✅ | Data is consistent and validated. |
| Authorized data access only | ❌ | All employees have access regardless of role. |

---

## 5&nbsp;&nbsp;Recommendations Summary

- **Limit data access** by enforcing least privilege.
- **Implement encryption** to protect sensitive and regulated data.
- **Develop disaster recovery plans** to ensure business continuity.
- **Enforce stronger password policies** and use a password management system.
- **Separate duties** to prevent fraud and internal misuse.
- **Classify assets** to align controls with asset value and sensitivity.
- **Deploy IDS and backup solutions** to improve threat detection and data resilience.

---

## 6&nbsp;&nbsp;Project Files

All `.docx` files included in this repository contain detailed documentation and templates relevant to the internal audit performed.

- View or download from the links above.

---

## 7&nbsp;&nbsp;License

This repository is intended for **portfolio and documentation purposes**. All content reflects a fictional business scenario created as part of a professional certificate project.
