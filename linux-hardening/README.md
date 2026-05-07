# Linux Hardening & Isolation

## Concepts

- Linux permissions and ownership
- capabilities vs root
- least privilege principle
- systemd sandboxing

## Resources

- man capabilities
- CIS Benchmarks (Linux basics)
- systemd.exec documentation

## Hands-on

- Analyze running services (ps, systemctl)
- Apply sandboxing:
  - NoNewPrivileges
  - PrivateTmp
  - ProtectSystem
  - ProtectHome
- Restrict capabilities via CapabilityBoundingSet

- Harden nginx.service using drop-in config

## Mini-Project

Linux Security Audit Script

Description:
Script that checks:
- dangerous permissions
- running services
- open ports
- basic misconfigurations
