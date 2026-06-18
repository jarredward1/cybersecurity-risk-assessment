# 🔍 iBank Financials — Cybersecurity Risk Assessment

> A structured risk assessment for a fictional publicly-traded financial institution, identifying critical assets, evaluating threats and vulnerabilities, and calculating risk scores using an established likelihood and impact framework.

---

## 📌 Overview

iBank Financials is a New York-based financial company offering insurance, annuities, investing, and cryptocurrency services across multiple U.S. locations. This risk assessment was conducted to identify and prioritize security risks across the organization's hybrid on-premise and cloud environment.

The assessment follows a structured process aligned with NIST RMF and supporting frameworks, producing risk scores for 11 critical assets using a 5x5 likelihood and impact matrix.

---

## 🏢 Case Study

iBank Financials is a publicly-traded financial company headquartered in New York City, with small remote offices across all major U.S. cities. Their products include insurance, annuities, investing, and a recently added cryptocurrency service.

### Environment

- **Main office in NYC** with 30 computers: 20 for client account management, 5 laptops for remote client work, and 5 for vendor and server management
- **Shared wireless network** with a partner insurance agency on the same floor
- **Remote office agents** each issued a laptop, connecting to the main office via VPN for client management and financial product access
- **Personal tablets** used by some agents to access the client management system over VPN without IT approval
- **6 servers** (on-premise and AWS) for access management, storage, client management, and vendor applications
- **Payment processing** via bank transfer, credit card, check, or account withdrawal with stored credit cards processed in daily batch runs

### The Problem

iBank's rapid growth created serious security gaps. When 15 new employees were hired, the following occurred:

| Decision | Security Impact |
|----------|----------------|
| President directed full server access for all new employees | Least privilege violation, massive insider threat exposure |
| System administrator complied without question | Governance failure, no access review process |
| HR issued universal badge access to all company areas | Physical security violation |
| IT deferred security configuration for sales laptops by one month | Unmanaged endpoints with full system access |
| Agents using personal tablets over VPN | Unvetted, unmanaged devices accessing sensitive systems |

These issues were not the result of a breach -- they were the result of a governance and process failure at the leadership level, creating significant unmanaged risk across the organization.

---

## 🛠️ Frameworks Applied

| Framework | Role |
|-----------|------|
| **NIST RMF** | Primary framework driving the assessment lifecycle |
| **ISO 31000** | Business-level risk perspective and financial impact |
| **FAIR** | Quantitative financial loss estimation |
| **OCTAVE** | Asset-focused threat and vulnerability analysis |
| **COBIT** | IT governance and access control accountability |
| **PCI DSS** | Payment card data compliance requirements |
| **NYDFS 23 NYCRR 500** | New York financial institution data protection standards |
| **SOX** | Financial reporting accuracy and fraud prevention |
| **KYC** | Cryptocurrency customer identity verification and AML compliance |

---

## 📊 Risk Assessment Results

Risk scores calculated using: **Likelihood (1-5) x Impact (1-5)**

| Asset | Likelihood | Impact | Risk Score | Level |
|-------|-----------|--------|-----------|-------|
| Customer Financial Data | 5 | 5 | 25 | Critical |
| Access Control System | 5 | 5 | 25 | Critical |
| Client Management System | 4 | 5 | 20 | Critical |
| Authentication Systems | 4 | 5 | 20 | Critical |
| Payment Processing System | 4 | 5 | 20 | Critical |
| Shared Wireless Network | 4 | 4 | 16 | Critical |
| Employee Laptops | 4 | 4 | 16 | Critical |
| VPN Infrastructure | 3 | 5 | 15 | High |
| Cloud Infrastructure (AWS) | 3 | 5 | 15 | High |
| New Employee Workstations | 4 | 3 | 12 | Medium |
| Vendor Applications | 3 | 4 | 12 | Medium |

---

## 🔢 Risk Scoring Matrix

| | Improbable (1) | Remote (2) | Occasional (3) | Probable (4) | Frequent (5) |
|---|---|---|---|---|---|
| **Catastrophic (5)** | 5 | 10 | 15 | 20 | 25 |
| **Significant (4)** | 4 | 8 | 12 | 16 | 20 |
| **Moderate (3)** | 3 | 6 | 9 | 12 | 15 |
| **Low (2)** | 2 | 4 | 6 | 8 | 10 |
| **Negligible (1)** | 1 | 2 | 3 | 4 | 5 |

---

## 📄 Documents

[View full risk assessment (PDF)](./Risk_Assessment.pdf)

[View case study (PDF)](./Case_Study.pdf)

---

## 👤 Author

**Jarred Ward**  
[LinkedIn](https://www.linkedin.com/in/jarredward1/)
