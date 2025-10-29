# D487 - Secure Software Design & Development

## Course Summary

This repository contains comprehensive study notes for WGU's D487 - Secure Software Design course. The course covers fundamental principles of software security, secure coding practices, threat modeling, and implementing security throughout the Software Development Life Cycle (SDLC). These notes are designed to help students understand core security concepts and prepare for the course assessment.

---

## Table of Contents

- [Chapter 1: Introduction to Software Security](#chapter-1--introduction-to-software-security)
  - [1.1 The Importance and Relevance of Software Security](#11-the-importance-and-relevance-of-software-security)
  - [1.2 Software Security and the SDLC](#12-software-security-and-the-sdlc)
  - [1.3 Quality vs. Secure Code](#13-quality-vs-secure-code)
  - [1.4 The CIA Triad](#14-the-cia-triad)
  - [1.5 Threat Modeling and Attack Surface Validation](#15-threat-modeling-and-attack-surface-validation)
- [Contributors](#contributors)

---

## Chapter 1 – Introduction to Software Security

### Chapter Overview

This chapter lays the foundation for software security. It explains why security matters, what goes wrong when it's ignored, and how security fits within the Software Development Life Cycle (SDLC).

**Key Learning Objectives:**
- Understanding what software security means and its distinction from network/IT security
- Recognizing why fixing security bugs early saves significant resources
- Differentiating between SDLC (software development process) and SDL (security development lifecycle)
- Protecting data using the CIA Triad: Confidentiality, Integrity, and Availability

**Quick Mnemonic:**
> **"CIA keeps software alive."**
> - **C** – Confidentiality → keep secrets safe
> - **I** – Integrity → keep data clean
> - **A** – Availability → keep systems running

---

### 1.1 The Importance and Relevance of Software Security

#### What the Research Shows

Software is ubiquitous—from smartphones to automobiles—and attackers are well aware of this. The majority of cyberattacks exploit vulnerabilities in code rather than network infrastructure.

#### Why It Matters

Even minor bugs can result in major losses. Organizations including DHS and the IT Advisory Committee have found that **70% of security flaws originate from poor software design**, not from hardware or network vulnerabilities.

**Analogy:**
> Think of your software like a car. If the engine (code) is faulty, fixing the paint job (network security) won't prevent it from breaking down.

#### Key Takeaway

**Good code = fewer vulnerabilities = fewer breaches**

Secure coding must begin at the design phase, not after release.

---

### 1.2 Software Security and the SDLC

#### What is SDLC?

The Software Development Life Cycle (SDLC) is the systematic process of building software: plan → design → code → test → deploy → maintain.

#### The Problem with Late Security Integration

Traditionally, developers treated security as an afterthought. However, fixing security issues late in development can cost up to **200× more** than addressing them during the design phase.

| When Flaw is Fixed | Cost Multiplier | Impact |
|-------------------|-----------------|--------|
| During design | 1× | Cheap and easy |
| During testing | 20× | Still manageable |
| After release | 200× | Costly and risky |

**Mnemonic:**
> **"Catch bugs when they're small – not when they're tall."**

---

### 1.3 Quality vs. Secure Code

#### Quality Code ≠ Secure Code

Software that functions well is not necessarily safe. A program can pass quality assurance testing while still exposing sensitive data like passwords.

#### Key Differences

| Quality Code | Secure Code |
|-------------|-------------|
| Works as expected | Works safely |
| Meets business needs | Protects users from harm |
| Tested for functionality | Tested for attack resistance |
| Focused on speed and UX | Focused on defense and control |

**Mnemonic: FAST vs. SAFE**
- **FAST** → Functional, Attractive, Stable, Tested
- **SAFE** → Secure, Authenticated, Fail-proof, Encrypted

---

### 1.4 The CIA Triad

The three most important security goals in the Security Development Lifecycle:

| Goal | Meaning | Example |
|------|---------|--------|
| **Confidentiality** | Only authorized individuals can access data | Encrypt passwords, implement access controls |
| **Integrity** | Data cannot be altered by unauthorized users | Use checksums, cryptographic hashing |
| **Availability** | Systems and data are accessible when needed | Implement backups, redundancy, DDoS protection |

**Analogy:**
> Think of CIA like protecting a house:
> - **C**: Lock your doors (control access)
> - **I**: Don't let anyone change your house number (prevent tampering)
> - **A**: Keep keys ready so family can enter anytime (ensure accessibility)

---

### 1.5 Threat Modeling and Attack Surface Validation

#### What is Threat Modeling?

Threat modeling is the process of creating a "security map"—identifying what can go wrong before it actually happens.

**Key Components:**
- **Assets**: What's valuable? (e.g., credit card data, user information)
- **Threats**: Who might attack? (e.g., external hackers, malicious insiders)
- **Vulnerabilities**: What weaknesses exist in the system?
- **Mitigations**: How can we reduce or eliminate risks?

#### Attack Surface

The attack surface represents all possible entry points where an attacker could attempt to exploit the system. Minimizing the attack surface is a fundamental security principle.

**Best Practices:**
- Reduce unnecessary features and entry points
- Implement principle of least privilege
- Validate all input from untrusted sources
- Regular security assessments and penetration testing

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
