# GRC Risk Assessment — F-Corp

**A simulated Governance, Risk & Compliance (GRC) engagement for a fictional 10-person e-commerce company, built as a portfolio project aligned to NIST CSF 2.0.**

---

## Overview

This project demonstrates practical GRC analyst skills by conducting a full risk assessment lifecycle for **F-Corp**, a fictional small e-commerce business processing customer payment data online. The engagement mirrors real-world GRC work: inventorying assets, identifying threats, scoring risk, recommending controls, and communicating findings to non-technical leadership.

**Frameworks Applied:**
- NIST Cybersecurity Framework (CSF) 2.0
- PCI-DSS v4.0 (payment data context)
- FTC Act (consumer data protection context)
- Qualitative Likelihood × Impact risk scoring (1–5 scale)

---

## Project Deliverables

| Document | Description |
|---|---|
| `Executive Summary` | Non-technical summary of findings and priority actions for leadership |
| `Asset Inventory` | 15 catalogued information assets with classification, ownership, and sensitivity ratings |
| `Risk Register` | 10 identified risks scored by likelihood and impact, with risk ratings and recommended controls |
| `Control Recommendations` | Security controls mapped to NIST CSF 2.0 functions and risk register entries |

---

## Scenario: F-Corp

F-Corp is a fictional 10-person e-commerce company operating an online retail storefront. The company:

- Processes customer credit card transactions via a third-party payment gateway (Stripe)
- Stores customer PII — names, addresses, order history — in a cloud-hosted database (AWS)
- Operates with no dedicated IT security staff
- Has no formal risk management program, incident response plan, or disaster recovery plan

**Engagement goal:** Identify F-Corp's most critical cyber risks, prioritize them by business impact, and recommend practical, cost-appropriate controls aligned to NIST CSF 2.0.

---

## Risk Scoring Methodology

Risks are scored using a qualitative matrix on a 1–5 scale:

```
Risk Score = Likelihood × Impact

Likelihood:  1 (Rare) → 5 (Almost Certain)
Impact:      1 (Negligible) → 5 (Catastrophic)

Score 1–4   → Low
Score 5–9   → Medium
Score 10–14 → High
Score 15–25 → Critical
```

---

## Risk Summary

| Risk ID | Asset | Threat | Score | Rating |
|---|---|---|---|---|
| R-001 | Customer PII Records | Data breach via unauthorized access | 20 | Critical |
| R-002 | Payment Gateway (Stripe) | Magecart skimming attack | 15 | High |
| R-003 | E-Commerce Web Application | SQL/code injection attack | 20 | Critical |
| R-004 | E-Commerce Web Application | DDoS attack causing downtime | 16 | High |
| R-005 | Admin / Privileged Accounts | Privilege abuse by insider | 15 | High |
| R-006 | Admin / Privileged Accounts | Credential compromise via phishing | 20 | Critical |
| R-007 | Cloud Hosting (AWS) | Misconfigured S3 bucket exposure | 12 | Medium |
| R-008 | Business Email System | Business Email Compromise (BEC) | 12 | Medium |
| R-009 | Backup System | Ransomware encrypts primary and backup systems | 20 | Critical |
| R-010 | Network Router / Firewall | Firewall misconfiguration exposes internal ports | 8 | Medium |

**Distribution: 4 Critical | 3 High | 3 Medium | 0 Low**

*See Risk Register for full scoring rationale and control mappings.*

---

## NIST CSF 2.0 Alignment

Controls are mapped across all six CSF 2.0 functions:

| Function | Focus Area |
|---|---|
| **Govern** | Risk management strategy, policies, roles and responsibilities |
| **Identify** | Asset inventory, risk assessment, business environment |
| **Protect** | Access control, awareness training, data security, encryption |
| **Detect** | Continuous monitoring, anomaly detection, log review |
| **Respond** | Incident response planning, communication procedures |
| **Recover** | Recovery planning, backup restoration, business continuity |

---

## Asset Inventory Summary

15 assets catalogued across five categories:

| Type | Count |
|---|---|
| Data | 3 |
| Software | 3 |
| Hardware | 4 |
| Service | 3 |
| People | 2 |

Assets classified by sensitivity (High / Medium / Low / None) and business importance (Critical / High / Medium / Low).

---

## Skills Demonstrated

- Asset classification, ownership assignment, and sensitivity rating
- Threat identification for small e-commerce environments (PII, PCI-DSS, BEC, ransomware)
- Qualitative risk scoring using Likelihood × Impact (1–5 scale)
- Control selection and mapping to NIST CSF 2.0 functions
- Executive communication — translating technical risk into business and financial terms
- Documentation consistent with real GRC analyst deliverables

---

## About

**Jerome Jones**
Cybersecurity student at Ivy Tech Community College | CompTIA Security+ (SY0-701) Candidate
Focused on GRC, risk management, and compliance roles.

[GitHub](https://github.com/JeromeJones7744) | [LinkedIn](https://www.linkedin.com/in/jeromejones)

---

*All company names, scenarios, and data in this project are entirely fictional and created for educational and portfolio purposes only. Framework references: NIST CSF 2.0, PCI-DSS v4.0, FTC Act.*
