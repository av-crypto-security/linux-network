# linux-network-labs
> ⚠️ This section is under active development and continuously extended.

Hands-on labs for Linux, networking, systems, and security fundamentals. 
Structured learning roadmap with daily logs and practical engineering tasks.
This repository is part of a 6-month intensive training plan aimed at
landing a Junior Security / Systems / Cloud Engineer position.

---

## Goals

- Build strong Linux fundamentals
- Practice service hardening and sandboxing
- Understand networking, firewalling, and packet flow
- Create documented security mini-projects for portfolio

---

## Planned Mini-Projects (Roadmap Preview)

This repository will contain the following hands-on mini-projects
developed during a 6-month engineering training plan:

### Linux & Systemd (Month 1)
- Custom systemd services with sandboxing and hardening
- systemd drop-in overrides (PrivateTmp, NoNewPrivileges, ProtectSystem)
- Hardened nginx service
- Linux Security Audit Script (20 security checks)

### Networking & Security Labs (Month 1)
- Isolated lab network (Kali / Web / Router)
- Firewall configuration with nftables
- Network scanning and analysis (nmap, traceroute)
- OpenVAS vulnerability scan + security report (PDF)
- nmap XML analyzer (Python)

### Python for Security & Automation (Month 2)
- Log parser (nginx / apache)
- Custom port scanner
- CVE lookup for outdated packages
- SBOM mini-parser
- Docker Security Scanner (policy-based)

### Web & Vulnerability Security (Month 3)
- DVWA labs (XSS, CSRF, SQLi)
- Web vulnerability reports with PoC and remediation
- Nuclei-based scanning

### Cloud & Infrastructure Security (Month 4)
- Secure cloud infrastructure (VPC, IAM, logging)
- Infrastructure as Code (Terraform)
- WireGuard VPN with Ansible automation

### SOC & Advanced Security (Month 5)
- Honeypot (OpenCanary) with logging and dashboard
- Basic threat detection and log analysis
- Cryptography & PQC authentication research (separate repo)

Final outcome: a documented, interview-ready portfolio for
Junior DevOps / Cloud Engineer (security-focused) roles.

---

## Lab Environment

Two virtual machines are used throughout the labs
(this setup will evolve during training):
| VM Name      | OS                     | Purpose                    |
|--------------|------------------------|----------------------------|
| ubuntu-lab   | Ubuntu 24.04 LTS       | systemd, journald, hardening |
| fedora-lab   | Fedora Workstation     | systemd, sandboxing tests  |

---

## Repository Structure

```
.
├── .gitignore
├── LICENSE
├── README.md
├── learning-log.md
├── docs/
│   └── screenshots/
├── systemd/
│   ├── custom-services/
│   └── hardening/
├── journald/
├── networking/
└── scripts/
└── projects/
    ├── linux-security-audit/
    ├── docker-security-scanner/
    └── cloud-secure-infra/
```
*(structure will evolve during training)*

---

## Learning Log

Daily progress, commands, observations, and conclusions are documented in
[`learning-log.md`](learning-log.md).

Each entry contains:
- date
- tasks performed
- commands used
- output / results
- personal notes

---

## Status

Week 1 — Linux fundamentals, systemd core, journald, sandboxing  
(actively developing)
