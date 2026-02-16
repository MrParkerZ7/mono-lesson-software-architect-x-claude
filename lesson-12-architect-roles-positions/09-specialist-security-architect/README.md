# Security Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Data Architect](../08-specialist-data-architect/README.md) | [Next: Infrastructure Architect](../10-specialist-infrastructure-architect/README.md)

---

## 9.1 Role Overview

The **Security Architect** designs and implements security controls, frameworks, and strategies to protect an organization's assets, data, and systems. They translate security requirements into technical solutions while balancing security with usability and business needs.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                     SECURITY ARCHITECT POSITION                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                        THREAT LANDSCAPE                                  │
│     ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐             │
│     │ External │  │ Internal │  │ Malware  │  │ Social   │             │
│     │ Attacks  │  │ Threats  │  │          │  │ Engineer │             │
│     └────┬─────┘  └────┬─────┘  └────┬─────┘  └────┬─────┘             │
│          │             │             │             │                     │
│          └─────────────┴──────┬──────┴─────────────┘                    │
│                               │                                          │
│                               ▼                                          │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                    SECURITY ARCHITECT                            │   │
│  │                                                                  │   │
│  │   PROTECTS                         DESIGNS                       │   │
│  │   ├── Applications                 ├── Security Controls        │   │
│  │   ├── Data                         ├── Authentication/AuthZ     │   │
│  │   ├── Infrastructure               ├── Encryption Strategy      │   │
│  │   ├── Networks                     ├── Threat Models            │   │
│  │   └── Identity                     └── Incident Response        │   │
│  │                                                                  │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                               │                                          │
│           ┌───────────────────┼───────────────────┐                     │
│           ▼                   ▼                   ▼                     │
│   ┌─────────────┐     ┌─────────────┐     ┌─────────────┐              │
│   │  Security   │     │  Compliance │     │   Secure    │              │
│   │  Posture    │     │   Status    │     │   Systems   │              │
│   └─────────────┘     └─────────────┘     └─────────────┘              │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Security Architecture Design** | Design security controls and frameworks | 25% |
| **Threat Modeling** | Identify and assess security risks | 20% |
| **Security Reviews** | Review architectures and code for security | 20% |
| **Compliance & Governance** | Ensure regulatory compliance | 15% |
| **Incident Response** | Design and support incident handling | 10% |
| **Security Awareness** | Train and advise teams | 10% |

### Security Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SECURITY ARCHITECTURE DOMAINS                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  IDENTITY & ACCESS                   APPLICATION SECURITY                │
│  ├── Authentication (MFA, SSO)       ├── OWASP Top 10                   │
│  ├── Authorization (RBAC, ABAC)      ├── Secure SDLC                    │
│  ├── Identity Governance             ├── Code Analysis (SAST/DAST)      │
│  ├── Privileged Access               ├── API Security                   │
│  └── Directory Services              └── Input Validation               │
│                                                                          │
│  DATA SECURITY                       NETWORK SECURITY                    │
│  ├── Encryption (at rest/transit)    ├── Segmentation                   │
│  ├── Data Classification             ├── Firewalls/WAF                  │
│  ├── DLP (Data Loss Prevention)      ├── Zero Trust                     │
│  ├── Key Management                  ├── VPN/Private Links              │
│  └── Tokenization                    └── IDS/IPS                        │
│                                                                          │
│  INFRASTRUCTURE SECURITY             SECURITY OPERATIONS                 │
│  ├── Hardening Standards             ├── SIEM/Logging                   │
│  ├── Patch Management                ├── Incident Response              │
│  ├── Container Security              ├── Threat Intelligence            │
│  ├── Cloud Security                  ├── Vulnerability Management       │
│  └── Endpoint Protection             └── Security Monitoring            │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                  SECURITY ARCHITECT WEEKLY SCHEDULE                      │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Security team standup                                      │
│  ├── 10:00  Architecture review (new project)                          │
│  ├── 14:00  Threat modeling session                                    │
│  └── 16:00  Security findings remediation review                       │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Vulnerability scan review                                  │
│  ├── 11:00  Security design for cloud migration                        │
│  ├── 14:00  Vendor security assessment                                 │
│  └── 16:00  Security documentation updates                             │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Security governance meeting                                │
│  ├── 11:00  Penetration test results review                            │
│  ├── 14:00  Developer security training                                │
│  └── 16:00  Compliance audit preparation                               │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Incident response drill                                    │
│  ├── 11:00  Security tool evaluation                                   │
│  ├── 14:00  Cross-team security consult                                │
│  └── 16:00  Security metrics reporting                                 │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly security review                                     │
│  ├── 11:00  Research: Emerging threats/solutions                       │
│  ├── 14:00  Policy and standard updates                                │
│  └── 16:00  Planning and prioritization                                │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Security Frameworks** | Expert | NIST, ISO 27001, CIS |
| **Identity & Access** | Expert | OAuth2, SAML, OIDC |
| **Cryptography** | Advanced | Encryption, PKI, HSM |
| **Network Security** | Advanced | Firewalls, VPN, Zero Trust |
| **Application Security** | Advanced | OWASP, secure coding |
| **Cloud Security** | Advanced | AWS/Azure/GCP security |
| **Threat Modeling** | Expert | STRIDE, PASTA, Attack Trees |

### Security Frameworks Knowledge

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SECURITY FRAMEWORKS                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  NIST CYBERSECURITY FRAMEWORK                                            │
│  ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐           │
│  │IDENTIFY │▶│ PROTECT │▶│ DETECT  │▶│ RESPOND │▶│ RECOVER │           │
│  │         │ │         │ │         │ │         │ │         │           │
│  │• Assets │ │• Access │ │• Monitor│ │• Plan   │ │• Plan   │           │
│  │• Risk   │ │• Train  │ │• Analyze│ │• Contain│ │• Restore│           │
│  │• Govern │ │• Data   │ │• Events │ │• Mitigate│ │• Improve│          │
│  └─────────┘ └─────────┘ └─────────┘ └─────────┘ └─────────┘           │
│                                                                          │
│  COMMON FRAMEWORKS                                                       │
│  ├── NIST CSF - Comprehensive security framework                       │
│  ├── ISO 27001 - Information security management                       │
│  ├── CIS Controls - Prioritized security actions                       │
│  ├── SOC 2 - Service organization controls                             │
│  ├── PCI DSS - Payment card security                                   │
│  ├── HIPAA - Healthcare data protection                                │
│  └── GDPR - Data protection regulation                                 │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Security Architecture Document** | Overall security design | All stakeholders |
| **Threat Models** | Risk identification and mitigation | Dev teams, security |
| **Security Standards** | Technical requirements | Development teams |
| **Security Review Reports** | Assessment findings | Project teams |
| **Incident Response Plans** | Response procedures | Security, operations |
| **Compliance Documentation** | Audit evidence | Auditors, compliance |

### Threat Modeling (STRIDE)

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    STRIDE THREAT MODEL                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  THREAT              DESCRIPTION                MITIGATION               │
│  ─────────────────────────────────────────────────────────────────────  │
│                                                                          │
│  S - Spoofing        Impersonating another      Authentication,         │
│      Identity        user or system             certificates            │
│                                                                          │
│  T - Tampering       Modifying data or code     Integrity checks,       │
│                                                  signing, hashing       │
│                                                                          │
│  R - Repudiation     Denying actions            Audit logging,          │
│                                                  digital signatures     │
│                                                                          │
│  I - Information     Unauthorized data          Encryption,             │
│      Disclosure      access                     access control          │
│                                                                          │
│  D - Denial of       Making system              Rate limiting,          │
│      Service         unavailable                redundancy              │
│                                                                          │
│  E - Elevation of    Gaining unauthorized       Least privilege,        │
│      Privilege       permissions                input validation        │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.6 Zero Trust Architecture

### Zero Trust Principles

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    ZERO TRUST ARCHITECTURE                               │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  CORE PRINCIPLES                                                         │
│  ├── Never trust, always verify                                         │
│  ├── Assume breach                                                      │
│  ├── Verify explicitly                                                  │
│  ├── Use least privilege access                                         │
│  └── Inspect and log all traffic                                        │
│                                                                          │
│  ZERO TRUST PILLARS                                                      │
│                                                                          │
│  ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐ ┌─────────┐           │
│  │IDENTITY │ │ DEVICES │ │NETWORKS │ │  APPS   │ │  DATA   │           │
│  │         │ │         │ │         │ │         │ │         │           │
│  │ • MFA   │ │ • MDM   │ │ • Micro-│ │ • SAST/ │ │ • Class-│           │
│  │ • SSO   │ │ • Health│ │   segment│ │   DAST  │ │   ify   │           │
│  │ • RBAC  │ │   Check │ │ • Encrypt│ │ • WAF   │ │ • Encrypt│          │
│  │ • Just- │ │ • Cert  │ │ • Private│ │ • AuthN/│ │ • DLP   │           │
│  │   in-time│ │        │ │   Access │ │   AuthZ │ │ • Rights│           │
│  └─────────┘ └─────────┘ └─────────┘ └─────────┘ └─────────┘           │
│                                                                          │
│  IMPLEMENTATION                                                          │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │                                                                  │    │
│  │  User ──▶ Identity ──▶ Device ──▶ Policy ──▶ Application        │    │
│  │            Provider     Check      Engine      Access            │    │
│  │                                      │                           │    │
│  │                              ┌───────┴───────┐                   │    │
│  │                              │   Continuous  │                   │    │
│  │                              │   Monitoring  │                   │    │
│  │                              └───────────────┘                   │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 8.7 Application Security

### Secure SDLC Integration

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SECURE SDLC                                           │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  PHASE          SECURITY ACTIVITIES                                      │
│  ─────────────────────────────────────────────────────────────────────  │
│                                                                          │
│  REQUIREMENTS   • Security requirements                                  │
│                 • Risk assessment                                        │
│                 • Compliance requirements                                │
│                                                                          │
│  DESIGN         • Threat modeling                                        │
│                 • Security architecture review                           │
│                 • Secure design patterns                                 │
│                                                                          │
│  DEVELOPMENT    • Secure coding standards                                │
│                 • SAST (Static Analysis)                                 │
│                 • Code review                                            │
│                 • Secrets management                                     │
│                                                                          │
│  TESTING        • DAST (Dynamic Analysis)                                │
│                 • Penetration testing                                    │
│                 • Security unit tests                                    │
│                 • Dependency scanning                                    │
│                                                                          │
│  DEPLOYMENT     • Configuration review                                   │
│                 • Infrastructure security                                │
│                 • Security smoke tests                                   │
│                                                                          │
│  OPERATIONS     • Vulnerability management                               │
│                 • Security monitoring                                    │
│                 • Incident response                                      │
│                 • Patch management                                       │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### OWASP Top 10

| Rank | Vulnerability | Mitigation |
|------|--------------|------------|
| 1 | Broken Access Control | RBAC, server-side validation |
| 2 | Cryptographic Failures | Strong encryption, key management |
| 3 | Injection | Parameterized queries, input validation |
| 4 | Insecure Design | Threat modeling, secure patterns |
| 5 | Security Misconfiguration | Hardening, configuration management |
| 6 | Vulnerable Components | Dependency scanning, updates |
| 7 | Authentication Failures | MFA, session management |
| 8 | Software Integrity Failures | Code signing, integrity checks |
| 9 | Logging Failures | Comprehensive logging, monitoring |
| 10 | SSRF | Input validation, network segmentation |

---

## 8.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SECURITY ARCHITECT CAREER PATH                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │   Security      │  │   Software      │  │    Network      │          │
│  │   Engineer      │  │   Developer     │  │   Engineer      │          │
│  │   (4+ years)    │  │   (5+ years)    │  │   (5+ years)    │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │       SECURITY        │                            │
│                    │       ARCHITECT       │                            │
│                    │      (3-5 years)      │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │   Principal     │  │      CISO       │  │   Enterprise    │         │
│  │Security Architect│ │                 │  │   Architect     │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications (High Value)

| Certification | Provider | Focus |
|---------------|----------|-------|
| CISSP | ISC2 | Comprehensive security |
| CCSP | ISC2 | Cloud security |
| CISM | ISACA | Security management |
| SABSA | SABSA Institute | Security architecture |
| AWS Security Specialty | AWS | AWS security |
| Azure Security Engineer | Microsoft | Azure security |

---

## 8.9 Sample Scenarios

### Scenario 1: Cloud Security Architecture

**Situation**: A financial services company is migrating to AWS and needs a secure cloud architecture.

**Security Architect Actions**:
1. Design multi-account structure with AWS Organizations
2. Implement landing zone with security guardrails
3. Design identity federation with existing AD
4. Create network security architecture (VPC, security groups)
5. Implement encryption strategy (KMS, key rotation)
6. Design logging and monitoring (CloudTrail, GuardDuty)
7. Create incident response procedures for cloud
8. Ensure PCI-DSS compliance in cloud environment

### Scenario 2: Zero Trust Implementation

**Situation**: Organization wants to move from perimeter-based security to Zero Trust.

**Security Architect Actions**:
1. Assess current security posture and gaps
2. Define Zero Trust maturity roadmap
3. Implement identity-centric security (MFA, SSO)
4. Design micro-segmentation strategy
5. Implement device trust verification
6. Deploy continuous monitoring and analytics
7. Create least-privilege access policies
8. Train teams on new security model

---

## 8.10 Comparison with Other Roles

| Aspect | Security Architect | Security Engineer | CISO |
|--------|-------------------|------------------|------|
| **Focus** | Design & strategy | Implementation | Governance & risk |
| **Hands-On** | Medium | High | Low |
| **Scope** | Technical security | Specific tools | Organization-wide |
| **Reports To** | CISO/CTO | Security Architect | CEO/Board |

---

## Key Takeaways

- Security Architects **design protection** into systems from the start
- **Threat modeling** is a core competency for identifying risks
- Must balance **security with usability** and business needs
- **Compliance knowledge** is essential in regulated industries
- Success requires **collaboration** with development and operations teams
- Continuous learning is critical as **threats constantly evolve**

---

## Practical Exercises

1. **Threat Modeling**: Conduct a STRIDE threat model for an e-commerce checkout flow.

2. **Security Review**: Review a sample architecture diagram and identify security concerns with recommendations.

3. **Zero Trust Design**: Create a Zero Trust architecture for a remote workforce scenario.

4. **Incident Response**: Design an incident response plan for a data breach scenario.

---

## Further Reading

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [OWASP Security Guides](https://owasp.org/)
- [Zero Trust Architecture (NIST SP 800-207)](https://csrc.nist.gov/publications/detail/sp/800-207/final)
- [Threat Modeling: Designing for Security by Adam Shostack](https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack/dp/1118809998)
