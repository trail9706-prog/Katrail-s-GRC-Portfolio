# Katrail-s-GRC-Portfolio
# GRC Case Study: SanDwane's (Carmerek Enterprise)

> **Training case study.** SanDwane's and SanDwane Labs are fictional organizations used in a cybersecurity GRC course. No real company or client data is included.

**Author:** Katrail Harris
**Focus areas:** Governance, Risk & Compliance · Incident Response · Third-Party Risk Management · Microsoft 365 / Azure security

---

## Scenario

SanDwane's is a pharmaceutical company running on Microsoft 365, SharePoint and Azure. After a data breach and a suspected insider leak of sensitive medication data to the press, the company engaged me to strengthen its security program across three assignments.

---

## Projects

### 1. Enterprise-Wide Cyber Incident Response Plan
📄 [`SanDwane's-Cyber-Incident-Response-Plan.docx`](./ SanDwane's Cyber Incident Response Plan.docx)

**Problem:** After a small breach, SanDwane's realised it had no procedure for engaging senior managers and stakeholders during an enterprise-wide cyber crisis.

**What I did:** Adapted a NIST SP 800-61 based government template into a 21-page plan tailored to Carmerek's environment, including:
- Four-level incident classification with pharma-specific impacts (patient safety, GxP systems, clinical data)
- Incident Management Team and Senior Executive Management Team roles, plus a **decision rights matrix**
- **Escalation matrix** with notification timeframes by severity
- Executive briefing format and meeting cadence during a crisis
- **Stakeholder notification matrix** (regulators, patients, investors, insurer, media)
- Out-of-band communications for when Microsoft 365 itself is compromised
- Response actions using Microsoft Defender XDR, Sentinel, Purview and Entra ID
- Appendices: situation update, incident log, resolution action plan, evidence register, critical assets, key contacts

### 2. Third-Party Risk Assessment: Horizon Labs (SaaS Supplier)
📊 [`TPRM_Carmerek_Labs_Assessment_Carmereks.xlsx`](./TPRM_Horizon_Labs_Assessment_Carmereks.xlsx)

**Problem:** Carmerek Labs provides a SaaS application that processes Carmerek's research intellectual property. Assess the supplier's security questionnaire and identify risks to escalate to senior management.

**What I did:** Reviewed 15 questionnaire responses, rated each risk, and produced an executive risk summary.

**Overall supplier risk: HIGH**

| Rating | Key finding |
|---|---|
| Critical | No role-based access control, least privilege, segregation of duties or access reviews |
| High | No security monitoring or incident response capability |
| High | No vulnerability scanning or penetration testing of an internet-facing SaaS |
| High | No security framework or independent assurance (ISO 27001 / SOC 2) |
| High | No DLP; backups mistaken for data protection |
| Medium | Encryption claims unverified; encryption in transit not addressed |
| Medium | Security training only at onboarding |
| Positive | MFA in place via Okta |

**Recommendation:** Continue only under formal risk acceptance, with a time-bound remediation plan, contractual security clauses (breach notification, right to audit, data deletion on exit), and compensating controls on Carmerek's side.

---

## Skills Demonstrated
- Incident response planning (NIST SP 800-61, NIST CSF 2.0)
- Crisis governance and executive stakeholder communication
- Third-party / vendor risk assessment and risk rating
- Regulatory awareness (GDPR, HIPAA, SEC disclosure, health regulators)
- Microsoft security stack: Defender XDR, Sentinel, Purview (DLP, Insider Risk, eDiscovery), Entra ID
