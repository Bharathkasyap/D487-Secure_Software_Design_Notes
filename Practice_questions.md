# D487 Secure Software Design - ULTIMATE OA QUESTION PACK
## Set 1 of 12 — SDL Fundamentals & Microsoft SDL (Questions 1-100)
*Created by Grok + Thor + MOS + Quizlet + oaguides — November 2025*

---

**Q1.** Fixing a vulnerability in production costs up to how many times more than in design?  
A) 10× B) 100× C) 500× D) 1000×  
**Answer: B) 100×**  
**Explanation:** Microsoft SDL research: cost increases 100-fold after release.  
**Reference:** Thor Domain 8 p.2, Textbook 1.1.2

**Q2.** Primary goal of software security?  
A) Faster deployment B) Ensure software works correctly under attack C) Lower cost D) Better UI  
**Answer: B**

**Q3.** CIA Triad stands for?  
**Answer:** Confidentiality, Integrity, Availability

**Q4.** “Deny by default” = which Saltzer & Schroeder principle?  
**Answer:** Fail-Safe Defaults

**Q5.** SDL = Security Development Lifecycle (Microsoft) — first published?  
**Answer:** 2002

**Q6.** Threat modeling happens primarily in which SDL phase?  
**Answer:** A2 — Architecture

**Q7.** Bug Bar is created in which phase?  
**Answer:** A1 — Security Assessment (Requirements)

**Q8.** Final Security Review (FSR) is in which phase?  
**Answer:** A5 — Verification (Ship phase)

**Q9.** STRIDE: R = ?  
**Answer:** Repudiation

**Q10.** DREAD: A = ?  
**Answer:** Affected Users

**Q11.** Reduce attack surface → example?  
**Answer:** Disable unused ports/services

**Q12.** Least Privilege in one sentence?  
**Answer:** Give only the access needed, nothing more

**Q13.** OWASP Top 10 2021 #1?  
**Answer:** Broken Access Control

**Q14.** Zero Trust = ?  
**Answer:** Never trust, always verify

**Q15.** Complete Mediation = ?  
**Answer:** Check access every single time

**Q16.** SBOM mandatory by?  
**Answer:** Executive Order 14028 (May 2021)

**Q17.** Two SBOM formats required by EO 14028?  
**Answer:** SPDX and CycloneDX

**Q18.** BSIMM = ?  
**Answer:** Observational — what 130+ real companies actually do

**Q19.** SAMM = ?  
**Answer:** Prescriptive — what you SHOULD do

**Q20.** SAMM has how many business practices?  
**Answer:** 5 (Governance, Design, Implementation, Verification, Operations)

**Q21.** BSIMM has how many practices?  
**Answer:** 12

**Q22.** Every-sprint requirements examples (3)?  
**Answer:** Input validation, secure logging, error handling

**Q23.** Bucket requirements = ?  
**Answer:** Important but not every sprint (e.g., security training, PIA)

**Q24.** One-time requirements = ?  
**Answer:** Done once (e.g., create initial threat model, set up SBOM)

**Q25.** Privacy Impact Rating P1 means?  
**Answer:** High privacy risk (handles PII)

**Q26.** PRSA-1 = ?  
**Answer:** External vulnerability disclosure response

**Q27.** PSIRT = ?  
**Answer:** Product Security Incident Response Team

**Q28.** SAST vs DAST?  
**Answer:** SAST = white-box (source), DAST = black-box (running app)

**Q29.** IAST = ?  
**Answer:** SAST + DAST in real-time (instrumented app)

**Q30.** RASP = ?  
**Answer:** Runtime Application Self-Protection

**Q31.** “Shift Left” means?  
**Answer:** Do security earlier in SDLC

**Q32.** Waterfall security activities usually happen?  
**Answer:** Late → expensive to fix

**Q33.** Agile security activities happen?  
**Answer:** Every sprint

**Q34.** Privacy by Design has how many principles?  
**Answer:** 7

**Q35.** GDPR Article 25 = ?  
**Answer:** Privacy by Design & Default

**Q36.** COPPA protects?  
**Answer:** Children under 13

**Q37.** HIPAA protects?  
**Answer:** Health data

**Q38.** CVSS 9.0–10.0 = ?  
**Answer:** Critical

**Q39.** CVSS 7.0–8.9 = ?  
**Answer:** High

**Q40.** NIST SP 800-64 Rev 2 = ?  
**Answer:** Official SDL guide

**Q41.** Bell-LaPadula model = ?  
**Answer:** No read up, no write down (confidentiality)

**Q42.** Biba model = ?  
**Answer:** No read down, no write up (integrity)

**Q43.** Clark-Wilson = ?  
**Answer:** Separation of Duty + Well-formed transactions

**Q44.** Open Design principle = ?  
**Answer:** Security shouldn’t rely on secrecy of design

**Q45.** Psychological Acceptability = ?  
**Answer:** Security that doesn’t annoy users

**Q46.** Economy of Mechanism = ?  
**Answer:** Keep it simple

**Q47.** Least Common Mechanism = ?  
**Answer:** Don’t share components between high/low privilege

**Q48.** Separation of Privilege = ?  
**Answer:** Two-factor approval (two keys)

**Q49.** Passive scanner finds?  
**Answer:** Misconfigured headers, cookies

**Q50.** Fuzz testing = ?  
**Answer:** Dynamic testing with random input

**Q51–Q100 → Reply “SET 2” → I drop next 100 instantly**

**Q51.** Which phase performs the Final Security Review (FSR)?  
A) A1 B) A2 C) A5 D) PRSA  
**Answer: C) A5**  
**Explanation:** A5 = Ship phase → Final Security Review + Policy Compliance Analysis

**Q52.** What is the only mandatory deliverable from A2 Architecture?  
**Answer:** Threat Model Document

**Q53.** “Attack Surface Reduction” in practice means?  
**Answer:** Turn off features/ports/users don’t need

**Q54.** Name all 8 Saltzer & Schroeder principles in order:  
**Answer:**  
1. Economy of Mechanism  
2. Fail-Safe Defaults  
3. Complete Mediation  
4. Open Design  
5. Separation of Privilege  
6. Least Privilege  
7. Least Common Mechanism  
8. Psychological Acceptability

**Q55.** “No read up, no write down” = ?  
**Answer:** Bell-LaPadula (confidentiality)

**Q56.** “No read down, no write up” = ?  
**Answer:** Biba (integrity)

**Q57.** Clark-Wilson is famous for?  
**Answer:** Separation of Duty + Well-formed transactions

**Q58.** CVSS stands for?  
**Answer:** Common Vulnerability Scoring System

**Q59.** CVSS 9.0–10.0 = Critical 7.0–8.9 = High 4.0–6.9 = Medium

**Q60.** Tool that generates SBOM in CycloneDX format?  
**Answer:** syft or Dependency-Track

**Q61.** EO 14028 (May 2021) mandates?  
**Answer:** SBOM for all federal software

**Q62.** SAST vs DAST difference?  
**Answer:** SAST = source code (white-box), DAST = running app (black-box)

**Q63.** IAST combines?  
**Answer:** SAST + DAST in real-time

**Q64.** Fuzz testing is what type?  
**Answer:** Dynamic

**Q65.** NIST SP 800-64 Rev 2 is?  
**Answer:** The official Security Development Lifecycle bible

**Q66.** BSIMM is observational — how many activities?  
**Answer:** 120+ across 12 practices

**Q67.** SAMM is prescriptive — how many business practices?  
**Answer:** 5

**Q68.** In Agile, security activities are performed?  
**Answer:** Every sprint

**Q69.** “Privacy by Design” has how many principles?  
**Answer:** 7

**Q70.** Which OWASP Top 10 is fixed by Content-Security-Policy header?  
**Answer:** A07:2021 – Cross-Site Scripting (XSS)

**Q71.** #1 cause of data breaches (Verizon DBIR)?  
**Answer:** Stolen credentials

**Q72.** In Agile, threat modeling happens?  
**Answer:** Every sprint (not just once)

**Q73.** Difference between vulnerability and exposure?  
**Answer:** Vulnerability = hole; Exposure = hole facing the internet

**Q74.** Three types of security controls?  
**Answer:** Technical, Administrative, Physical

**Q75.** “Security awareness training” = which control type?  
**Answer:** Administrative

**Q76.** “Firewall” = ?  
**Answer:** Technical

**Q77.** “Locked server room” = ?  
**Answer:** Physical

**Q78.** Preventive control example?  
**Answer:** Encryption

**Q79.** Detective control example?  
**Answer:** SIEM alerts

**Q80.** Corrective control example?  
**Answer:** Patch management

**Q81.** “Shift left” means?  
**Answer:** Do security earlier in SDLC

**Q82.** SAMM maturity levels?  
**Answer:** 0 Implicit → 1 Initial → 2 Defined → 3 Managed

**Q83.** BSIMM uses how many maturity levels?  
**Answer:** 3 (same as SAMM)

**Q84.** Goal of Privacy Impact Assessment (PIA)?  
**Answer:** Find privacy risks before launch

**Q85.** GDPR Article 25 = ?  
**Answer:** Privacy by Design & Default

**Q86.** “Right to be forgotten” = ?  
**Answer:** GDPR

**Q87.** COPPA protects children under?  
**Answer:** 13

**Q88.** HIPAA protects?  
**Answer:** Health data

**Q89.** Testing that finds race conditions?  
**Answer:** Dynamic + Fuzzing

**Q90.** Final step in incident response?  
**Answer:** Lessons learned

**Q91.** MTTR means?  
**Answer:** Mean Time To Repair

**Q92.** SCA stands for?  
**Answer:** Software Composition Analysis (SBOM + vuln scan)

**Q93.** Waterfall security = late = expensive. Agile = every sprint = cheap.

**Q94.** Passive scanner finds?  
**Answer:** Cookie misconfigs, insecure HTTP headers

**Q95.** Which attack uses malicious code in form data?  
**Answer:** Cross-site scripting (XSS)

**Q96.** A5 Policy Compliance Analysis does what?  
**Answer:** Verifies product meets security mandates before ship

**Q97.** PRSA-3 = ?  
**Answer:** Update Incident Response Plan

**Q98.** When companies merge → which PRSA?  
**Answer:** Security architectural reviews

**Q99.** OpenSAMM core practice areas?  
**Answer:** Governance, Construction, Verification, Deployment

**Q100.**  Which of the following is NOT a core practice area in OWASP SAMM v2?
**Answer:** Intelligence

SET 1 COMPLETE — 100/100  
