# D487 - Secure Software Design Notes

## 📋 Table of Contents

1. [Overview](#overview)
2. [SDL Maturity Models](#sdl-maturity-models)
3. [Threat & Risk Management](#threat--risk-management)
4. [SDL Phase Comparison](#sdl-phase-comparison)
5. [Final SDL Formula](#final-sdl-formula)
6. [Quick Recap Reference](#quick-recap-reference)
7. [Closing Analogy](#closing-analogy)
8. [Case Study: Revvin' Engines](#case-study-revvin-engines)
9. [Answer Keys Highlights](#answer-keys-highlights)
10. [Visual Resources](#visual-resources)
11. [Contributors](#contributors)

---

## Overview

**Goal:** Adapt SDL to Agile, DevOps, Cloud, or Enterprise.

**Maturity Models:** BSIMM (observe others), SAMM (build your roadmap).

**Threat Enhancements:** MITRE ATT&CK + DEFEND models.

**Future:** Security automation + DevSecOps.

**🎯 Mnemonic:** "AIMS" → Adapt, Integrate, Measure, Strengthen.

**💡 Analogy:** Like tuning one car engine for different racetracks — same core, different setups.

---

## SDL Maturity Models

### Comparison Table

| Model | Purpose | Focus Areas | Mnemonic |
|-------|---------|-------------|----------|
| **SAMM** | Build your roadmap | Governance, Construction, Verification, Deployment, Education | GCVDE |
| **BSIMM** | Learn from others | Governance, Intelligence, SSDL, Deployment | GISD |

**💡 Analogy:**
- SAMM = GPS (guidance)
- BSIMM = Dashboard (status)

---

## Threat & Risk Management

### Core Concepts & Mnemonics

| Concept | Mnemonic | Meaning |
|---------|----------|----------|
| **Threat Modeling Steps** | THREAT | Identify, Survey, Decompose, Threats, Vulns |
| **Risk Rating** | DREAD | Damage, Reproducibility, Exploitability, Affected Users, Discoverability |
| **Response Plan** | IVAPT | Identify, Verify, Assign, Patch, Track |
| **CVSS Severity** | LMHC | Low, Medium, High, Critical |
| **PSIRT Workflow** | RVCD | Receive, Verify, Coordinate, Document |
| **Continuous Improvement** | RUTR | Review, Update, Train, Refine |

---

## SDL Phase Comparison

### Quick Phase Reference Table

| Phase | Focus | Mnemonic | Output |
|-------|-------|----------|--------|
| **A1** | Security Assessment | DPT | Risk + PIA |
| **A2** | Architecture | THREAT+DREAD | Threat Models |
| **A3/A4** | Design & Development | EEL / VSAFE | Secure Code |
| **A5** | Verification | PC | Testing Reports |
| **PRSA** | Post-Release | SUPPORT | Patches + Monitoring |

---

## Final SDL Formula

### The Formula to Remember

```
SDL = P² + A³ + S⁵
```

**Where:**
- **P²** = Plan + Protect
- **A³** = Assess + Architect + Automate
- **S⁵** = Secure + Scan + Share + Sustain + Strengthen

**🎯 Mnemonic Summary:**
> "Plan it, Protect it, Perfect it."

---

## Quick Recap Reference

### Boss Quick Recap Table

| Area | Mnemonic | Memory Line |
|------|----------|-------------|
| **SDL Essence** | SECURE | Secure Early, Continuously Update, Review Everything |
| **Risk Mgmt** | DREAD | Standard risk scoring model |
| **Threat Modeling** | THREAT | Identify to Vulnerability |
| **Post-Release** | SUPPORT | Maintain after release |
| **Adaptation** | AIMS | Adapt SDL for any environment |
| **Culture** | TEAM | Train, Empower, Align, Measure |
| **Future Outlook** | GOOD | Governed, Optimized, Ongoing, Detectable |

---

## Closing Analogy

### 🧭 SDL = The Software's Immune System

- **A1 (Assessment):** Diagnosis
- **A2 (Architecture):** Treatment plan
- **A3/A4 (Development):** Medicine applied
- **A5 (Verification):** Health check
- **PRSA (Post-release):** Continuous monitoring

---

## Case Study: Revvin' Engines

### 🧩 Appendix A – Case Study Details

| Event | Summary |
|-------|----------|
| **Who** | Revvin' Engines Auto Parts, new dev team (C#, tester, designer, lead). |
| **Issue** | SQL Injection caused customer credit card leaks. |
| **Action** | Forensics → Shut down → Fix DB → Implement SDL. |
| **Lesson** | Security is not optional — build it from day one. |

**🎯 Mnemonic:** "R-E-V-V-I-N" → Root cause, Enforce SDL, Validate, Verify, Involve, Never ignore.

**💡 Analogy:** Like forgetting to lock your door — by the time thieves come, it's too late.

---

## Answer Keys Highlights

### 🧾 Appendix B – Chapter Answer Keys

| Chapter | Mnemonic | Core Answer Summary |
|---------|----------|---------------------|
| **1** | RCIA | Security costs 200× more post-release; focus on CIA. |
| **2** | DPLB | Start at design, least privilege, BSIMM. |
| **3** | DPT | Discovery → PIA → Threat. |
| **4** | THREAT+DREAD | Identify & score threats. |
| **5** | EEL | Simplicity in design. |
| **6** | VSAFE | Validate, Secure, Avoid leaks. |
| **7** | PC | Define procedures & corrections. |
| **8** | RDM | Resolve, Drill, Mix diverse teams. |

---

## Visual Resources

<img width="557" height="30999" alt="image" src="https://github.com/user-attachments/assets/2132e930-e1f3-497f-b87c-6490b43dacfc" />

---

## Contributors

Contributions to these notes are welcome! If you'd like to improve the content, fix errors, or add additional study materials:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add study improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

**Maintainer:** [@Bharathkasyap](https://github.com/Bharathkasyap)

---

*Last Updated: October 2025*

*These notes are for educational purposes. Please refer to official WGU course materials for complete information.*
