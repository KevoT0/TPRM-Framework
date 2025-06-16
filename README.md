# TPRM-Framework

# 🔐 Third-Party Risk Management Framework — PaySecure Capital

## 🏢 Company Overview

- **Company Name:** PaySecure Capital  
- **Industry:** Financial Services (FinTech)  
- **Business Model:** Provides digital payment infrastructure and financial management tools  
- **Organization Size:** 500 Employees  
- **Compliance Goals:** ISO/IEC 27001:2022, PCI DSS, GDPR  

---

## 📌 Project Title

**Development of a Third-Party Risk Management Framework for PaySecure Capital, a Financial Technology Company**

---

## 🔍 Vendors in Scope

| Vendor | Function | Data Handled |
|--------|----------|---------------|
| **Okta** | Identity & Access Management | PII, Authentication Logs |
| **Adyen** | Payment Processing | Financial Data, PCI Data |

---

## 📋 Vendor Security Assessment

| Category | Question | Okta | Adyen |
|----------|----------|------|-------|
| **General** | Where is the vendor headquartered and where do they operate? | San Francisco, Global | Amsterdam, Global |
| | Do they use subcontractors? | Yes | Yes |
| **Security** | Do they have an Information Security Policy? | Yes | Yes |
| | Is customer data encrypted at rest and in transit? | Yes | Yes |
| | Do they perform regular penetration testing and vulnerability scans? | Yes | Yes |
| **Privacy & Compliance** | Do they handle PII, PHI, or PCI data? | Yes | Yes |
| | Are they compliant with GDPR, HIPAA, etc.? | Yes | Yes |
| | Do they hold certifications (e.g., ISO 27001, SOC 2)? | Yes | Yes |
| | Do they have defined breach notification timelines? | Yes | Yes |
| **Access Controls** | Do they support SSO and MFA? | Yes | Yes |
| | Is access to customer data logged and restricted? | Yes | Yes |
| | Can access be revoked quickly? | Yes | Yes |

---

## 📊 Vendor Risk Matrix

| Vendor | Likelihood (1–5) | Impact (1–5) | Risk Score | Risk Level |
|--------|------------------|--------------|------------|-------------|
| Okta | 4 | 4 | 16 | High |
| Adyen | 5 | 5 | 25 | High |

### 🎯 Vendor Tiering

- **Tier 1** — High Risk Vendors (e.g., Okta, Adyen)

---

## ✅ ISO 27001:2022 Control Mapping

| ISO Control | Name | Alignment Summary |
|-------------|------|-------------------|
| A.5.19 | Information security in supplier relationships | Vendors are assessed pre-onboarding to ensure security posture |
| A.5.20 | Addressing security in supplier agreements | Contracts include encryption, breach notification SLAs, access control terms |
| A.5.22 | Monitoring and review of supplier services | Periodic reassessments and compliance updates are required |
| A.5.23 | Information security for use of cloud services | Vendors must meet encryption, access, and cloud security benchmarks |

---

## 📝 Key Contractual Clauses

| Clause Type | Description | ISO Ref |
|-------------|-------------|---------|
| Data Security | Encrypt customer data in transit and at rest | A.5.12 |
| Breach Notification | Notify PaySecure within 72 hours of a breach | A.6.8 |
| Regulatory Compliance | Comply with GDPR, PCI DSS, ISO 27001 | A.5.31 |
| Right to Audit | Annual audit rights or post-incident audit access | A.5.20 |
| Subprocessor Management | Require disclosure and approval for subprocessors | A.5.20 |
| Access Control | Role-based access with logging and MFA | A.5.15 |
| Data Retention | Secure deletion or return of data after termination | A.8.10 |
| Business Continuity | Maintain and test DR/BCP plans | A.5.30 |
| Termination for Breach | Right to terminate for major security failure | A.5.20 |

---

## 🔄 Ongoing Monitoring Questions

| Question | Purpose |
|----------|---------|
| Do vendors notify about changes in security posture? | Detect new risks early |
| Are SLAs reviewed periodically? | Ensure performance and security standards |
| Is risk tiering re-evaluated? | Maintain up-to-date classification |
| Do vendors maintain their certifications? | Validate ISO/SOC/GDPR status |
| Are updated security questionnaires submitted? | Confirm control effectiveness |
| Is performance documented? | Analyze incident trends and SLA breaches |
| Is there a formal communication channel? | Ensure direct access to key contacts |

---

## 🚨 Incident Response Table

| What Happened | Risk Level | Initial Response | Remediation | Timeline | Escalation | Owner |
|---------------|------------|------------------|-------------|----------|------------|--------|
| Okta lacked encryption at rest | Medium | Communicated to vendor | Full encryption implementation | 30 days | Escalate to CISO if not resolved | Compliance Officer |
| Adyen had no breach SLA | Medium | Reviewed terms | Update contract | 3 weeks | Escalate to CISO | Legal / HR |
| Adyen lacks SOC 2 | High | Informed stakeholders | SOC 2 roadmap and audit | 2 months | Escalate to CISO | Compliance Officer |
| Okta had no admin restrictions | High | Reviewed access policy | Update policy + MFA | 1 month | Escalate to CISO | HR / Compliance |

---

## 📁 Exception Management

| Exception | Risk Level | Accepted? | Mitigation | Owner | Review Date |
|-----------|------------|-----------|------------|--------|--------------|
| Adyen — No SOC 2 | High | ✅ Temporarily | Vendor roadmap for SOC 2 audit | Compliance Officer | 31-Aug-2025 |
| Adyen — No breach SLA | Medium | ✅ Yes | Contract update in process | Legal | 15-Jul-2025 |
| Okta — No encryption at rest | Medium | ❌ No | Vendor to fix in 30 days | IT Security | 30-Jun-2025 |
| Okta — No admin access controls | High | ✅ Conditionally | Require updated access policy | CISO | 10-Jul-2025 |

---

## 📆 Vendor Review Schedule

| Vendor | Last Review | Next Review | Status Change | Follow-Up Needed? | Notes |
|--------|-------------|-------------|----------------|--------------------|-------|
| Okta | Jan 2025 | Jul 2025 | None | ❌ No | All controls validated |
| Adyen | Jan 2025 | Jul 2025 | New subprocessor added | ✅ Yes | Revalidate compliance |

---

> 💡 *This project aligns with ISO/IEC 27001:2022 best practices and demonstrates real-world application of third-party governance in FinTech.*

#TPRM #ISO27001 #VendorRisk #FinTechSecurity #RiskManagement #Compliance #GDPR #PCIDSS
