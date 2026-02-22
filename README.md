# mikrotik-smb-security-baseline
Practical security baseline configuration for MikroTik in SMB networks (segmentation, firewall, VPN, logging).
# MikroTik Secure Baseline for SMB Networks

This repository contains a practical, security-focused baseline for MikroTik routers deployed in small and mid-sized business (SMB) environments.

## Read the article
- **Article 01:** [How to Build a Secure MikroTik Baseline Configuration for Small Business Networks](articles/01-secure-baseline.md)

## What this baseline covers
- Router self-protection (Input chain hardening)
- Segmentation strategy (VLAN model for SMB)
- Forward chain security (least privilege traffic flows)
- VPN-only remote access (no exposed internal services)
- Logging & monitoring fundamentals
- Backup & recovery checklist

## Recommended VLAN Model
| VLAN | Purpose |
|------|---------|
| 10 | Management |
| 20 | Users |
| 30 | Guest |
| 40 | IoT |
| 50 | Servers (optional) |

## Disclaimer
Always test in a lab before deploying to production. Adapt rules and addressing to your environment.

---
Part of the ongoing **“MikroTik Security for SMB”** series.
