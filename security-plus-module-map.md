# CompTIA Security+ (SY0-701) — 12-Module Map

Exam version V7, series code SY0-701, launched November 7, 2023.
Maximum 90 questions in 90 minutes; passing score 750 on a 100–900 scale.

Fifteen-week semester: 12 module weeks plus unit exams in Weeks 5, 10, and 15.

Built against the `interactive-textbook-module` skill. Each module is a
standalone HTML file; the schedule, labs, and exams live in Canvas.

---

## Domain allocation

| Domain | Exam weight | Modules | Course share | Deviation |
|---|---|---|---|---|
| 1 · General security concepts | 12% | 2 | 16.7% | +4.7 |
| 2 · Threats, vulnerabilities, and mitigations | 22% | 3 | 25.0% | +3.0 |
| 3 · Security architecture | 18% | 2 | 16.7% | −1.3 |
| 4 · Security operations | 28% | 3 | 25.0% | −3.0 |
| 5 · Security program management and oversight | 20% | 2 | 16.7% | −3.3 |
| **Total** | **100%** | **12** | | |

Twelve modules divide evenly into three four-module units, one per exam. Every
module is assessed and none falls after the final exam.

Allocation notes:

- **Domain 1 gets 2 modules instead of 1.4.** Objective 1.4 (PKI, encryption,
  hashing, digital signatures, blockchain) is dense enough to need its own
  module. This is the largest single deviation, at +4.7 points.
- **Domain 4 absorbs the cut, dropping from 4 modules to 3.** Of the three ways
  to reach 12, cutting a Domain 4 module produced the smallest average deviation
  from exam weight (3.1 points, versus 4.0 for cutting Domain 2 and 3.3 for
  cutting Domain 1). The cost is that Module 10 is the densest module in the
  course, carrying four objectives.
- **Domain 4 is now 3 points light against a 28% exam weight.** Compensate in
  the Module 8–10 question banks by weighting toward applied and scenario tiers
  rather than adding contact time.

## Modules

### Domain 1 — General security concepts (12%)

**Module 1 · Security Fundamentals and Controls** — objectives 1.1–1.3
CIA triad, non-repudiation, AAA, authenticating people vs systems, gap analysis,
zero trust (control plane and data plane), physical security, deception and
disruption technology, security control categories and types, change management
processes and technical implications, documentation, version control.

**Module 2 · Cryptographic Solutions** — objective 1.4
PKI, public and private keys, key escrow, encryption levels, transport vs data
at rest, algorithms, key length, trusted execution environments, obfuscation,
steganography, tokenization, data masking, hashing, salting, digital signatures,
key stretching, blockchain, open public ledger, certificates, CAs, CRLs, OCSP,
self-signed certificates, certificate signing requests.

### Domain 2 — Threats, vulnerabilities, and mitigations (22%)

**Module 3 · Threat Actors and Attack Surfaces** — objectives 2.1–2.2
Nation-state, unskilled attacker, hacktivist, insider threat, organized crime,
shadow IT; attributes including internal/external, resources, sophistication;
motivations from data exfiltration through espionage and financial gain. Threat
vectors: message-based, image-based, file-based, voice call, removable device,
vulnerable software, unsupported systems, unsecure networks, open service ports,
default credentials, supply chain, and human vectors including social engineering.

**Module 4 · Vulnerabilities** — objective 2.3
Application vulnerabilities including memory injection, buffer overflow, and race
conditions; OS-based, web-based (SQLi, XSS), hardware (firmware, end-of-life,
legacy), virtualization (VM escape, resource reuse), cloud-specific, supply chain,
cryptographic, misconfiguration, mobile device, and zero-day vulnerabilities.

**Module 5 · Malicious Activity and Mitigation** — objectives 2.4–2.5
Malware attacks, physical attacks, network attacks including DDoS and on-path,
application attacks, cryptographic attacks, password attacks, and indicators of
compromise. Mitigation through segmentation, access control, application
allow-listing, isolation, patching, encryption, monitoring, least privilege,
configuration enforcement, decommissioning, and hardening techniques.

### Domain 3 — Security architecture (18%)

**Module 6 · Architecture Models and Enterprise Infrastructure** — objectives 3.1–3.2
Cloud responsibility matrix, hybrid and third-party considerations, IaC,
serverless, microservices, network infrastructure, air-gapped and logical
segmentation, SDN, on-premises, centralized vs decentralized, containerization,
virtualization, IoT, ICS/SCADA, RTOS, embedded systems, availability and
resilience considerations. Infrastructure: device placement, security zones,
attack surface, connectivity, failure modes, device attributes, network
appliances, port security, firewall types, secure communication, VPN, remote
access, tunneling, SD-WAN, SASE.

**Module 7 · Data Protection, Resilience, and Recovery** — objectives 3.3–3.4
Data types and classifications, general data considerations including data
states, sovereignty, and geolocation; protection methods including geographic
restrictions, encryption, hashing, masking, tokenization, obfuscation,
segmentation, and permission restrictions. High availability, site
considerations, platform diversity, multi-cloud, continuity of operations,
capacity planning, testing, backups, and power resilience.

### Domain 4 — Security operations (28%)

**Module 8 · Secure Baselines, Hardening, and Asset Management** — objectives 4.1–4.2
Secure baselines (establish, deploy, maintain), hardening targets, wireless
devices and installation considerations, mobile solutions including MDM, BYOD,
COPE, and CYOD; connection methods, wireless security settings including WPA3
and AAA/RADIUS, application security, sandboxing, and monitoring. Asset
acquisition, assignment and accounting, monitoring and tracking, disposal and
decommissioning, sanitization, destruction, certification, and data retention.

**Module 9 · Vulnerability Management, Monitoring, and Enterprise Controls** — objectives 4.3–4.5
Identification methods including vulnerability scans, application security
testing, threat feeds, OSINT, penetration testing, responsible disclosure, and
bug bounty. Analysis: confirmation, false positives and negatives,
prioritization, CVSS, CVE, exposure factor, environmental variables, and risk
tolerance. Remediation, validation, and reporting. Monitoring computing
resources and activities, alerting, alert tuning, SCAP, benchmarks, agent vs
agentless, SIEM, antivirus, and DLP. Enterprise controls: firewall rules and
configuration, screened subnets, IDS/IPS, web filtering, URL scanning, DNS
filtering, email security including DMARC, DKIM, and SPF, file integrity
monitoring, NAC, EDR/XDR, and user behavior analytics.

**Module 10 · Identity, Automation, Incident Response, and Forensics** — objectives 4.6–4.9
Provisioning and deprovisioning, permission assignments, identity proofing,
federation, SSO, LDAP, OAuth, SAML, interoperability, attestation, access
control models, MFA factors, password concepts, and privileged access
management. Automation and orchestration use cases and benefits including
efficiency, baseline enforcement, and reaction time, with considerations
including complexity, cost, technical debt, and single point of failure.
Incident response process, training, testing including tabletop exercises,
root cause analysis, threat hunting, and digital forensics covering legal hold,
chain of custody, acquisition, reporting, preservation, and e-discovery. Log
data and investigation data sources.

> **Density warning.** Module 10 carries four objectives and is the heaviest in
> the course. If any module needs to be split across two class sessions or
> supplemented with a Canvas assignment, it is this one.

### Domain 5 — Security program management and oversight (20%)

**Module 11 · Governance and Risk Management** — objectives 5.1–5.2
Guidelines, policies, standards, and procedures; external considerations
including regulatory, legal, industry, local/regional, national, and global;
monitoring and revision, governance structures, and roles and responsibilities.
Risk identification, assessment, analysis including qualitative, quantitative,
SLE, ALE, and ARO; risk register, key risk indicators, risk appetite and
tolerance, risk management strategies, reporting, and business impact analysis
including RTO, RPO, MTTR, and MTBF.

**Module 12 · Third-Party Risk, Compliance, and Awareness** — objectives 5.3–5.6
Vendor assessment, penetration testing, right-to-audit clause, evidence of
internal audits, supply chain analysis, vendor selection and due diligence,
conflict of interest, agreement types including SLA, MOA, MOU, MSA, WO/SOW,
NDA, and BPA, and vendor monitoring. Compliance reporting, consequences of
non-compliance, attestation and acknowledgement, privacy including data
inventory, right to be forgotten, and data roles. Attestation, internal and
external audits, penetration testing types, and security awareness practices
including phishing campaigns, anomalous behavior recognition, and reporting.

---

## 15-week schedule

Three unit exams in Weeks 5, 10, and 15. No exam is cumulative; each covers only
the four modules in its unit.

| Week | Content |
|---|---|
| 1–4 | Modules 1–4 |
| 5 | **Unit Exam 1** — Modules 1–4 |
| 6–9 | Modules 5–8 |
| 10 | **Unit Exam 2** — Modules 5–8 |
| 11–14 | Modules 9–12 |
| 15 | **Unit Exam 3** — Modules 9–12 |

Twelve module weeks, three exam weeks, no orphan content: every module is
covered by an exam, and the last module is taught the week before the last exam.

### Exams do not align to domain boundaries

Domain boundaries fall after modules 2, 5, 7, and 10. Exam boundaries fall after
4, 8, and 12. These cannot be reconciled — the domain blocks are 2/3/2/3/2, and
no ordering of them produces cumulative sums of 4, 8, and 12.

Consequence: every exam except the first spans multiple domains, and Unit Exam 2
spans three. Define each exam by its module range rather than by domain, and
tell students to study by module. Review materials organized by domain will give
students the wrong scope for Exam 2.

| Assessment | Week | Covers | Domains touched |
|---|---|---|---|
| Unit Exam 1 | 5 | Modules 1–4 | 1, 2 |
| Unit Exam 2 | 10 | Modules 5–8 | 2, 3, 4 |
| Unit Exam 3 | 15 | Modules 9–12 | 4, 5 |

### No slack in the calendar

Fifteen weeks with three exam weeks leaves no review week and no buffer. A snow
day, a campus closure, or a holiday landing on a class day costs a module week
directly. Two mitigations worth considering: designate Module 10 as the
split-across-two-sessions candidate if time allows, and keep one module's
delivery flexible enough to move to asynchronous Canvas work.

## Per-module conventions

- Storage key prefix: `secplus_mNN_v1` — must differ from the CEH prefix so
  progress does not collide in the same browser.
- Section count: 6–9 per module, `overview` first and `assessment` last.
- The mandatory `countermeasures` slot from the CEH pattern does not fit
  Domains 1 and 5. For governance, risk, and cryptography modules that slot
  becomes `implementation`, `assessment-methods`, or `applied-practice`.
- Question bank: 20–30 items, 80% to pass, ~30% recall / ~45% applied /
  ~25% scenario.

## Version watch

SY0-801 preview is tentatively around October 20, 2026, with SY0-701 retiring
roughly six months after 801 goes live. The headline addition is AI: dedicated
LLM coverage and AI in threats and vulnerabilities. That date has not been
confirmed and CompTIA has historically slipped release dates.

Mitigation already built into this map: AI-adjacent content stays in its own
subsections rather than being woven throughout, so the 801 refresh is an
additive pass. Candidate landing spots are Module 3 (AI-enabled threat actors),
Module 4 (model and prompt vulnerabilities), and Module 8 (securing AI
workloads).
