<div align="center">

# Mohammad Ahmadi

**Security analyst · Detection engineering · Purple-team tooling**

Denver, CO · B.S. Cybersecurity, December 2026

[![Portfolio](https://img.shields.io/badge/Portfolio-m3tan01.github.io-0E5A78?style=for-the-badge)](https://m3tan01.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mohammadma-1F5CA6?style=for-the-badge)](https://www.linkedin.com/in/mohammadma/)

![Security+](https://img.shields.io/badge/CompTIA-Security%2B-B03A30?style=flat-square)
![Network+](https://img.shields.io/badge/CompTIA-Network%2B-B03A30?style=flat-square)
![Defender XDR](https://img.shields.io/badge/Microsoft-Defender%20XDR-0E5A78?style=flat-square)
![KQL](https://img.shields.io/badge/Detections-KQL%20%C2%B7%20Sigma-1F5CA6?style=flat-square)

</div>

---

I triage alerts and incidents in Microsoft Defender XDR and remediate them, write KQL detections for privilege escalation, lateral movement and data exfiltration, and build open-source tooling that lets red and blue agents test each other.

## Projects

| Project | What it is | Stack |
|---|---|---|
| **[OpenElia](https://github.com/M3tan01/OpenElia)** | AI-assisted purple-team platform. Red, blue and reporter agents coordinate over the Model Context Protocol. | Python · MCP · Atomic Red Team · Docker |
| **[WireGuard VPN Implementation](https://github.com/M3tan01/WireGuard-VPN-Server)** | Bash-automated WireGuard server with Curve25519 and ChaCha20, plus a step-by-step guide covering firewall rules, SSH hardening and leak tests. | WireGuard · Bash · Ubuntu · UFW |
| **Network Security Assessment** | Course project (Defensive Cyber Operations): three-week assessment of a simulated healthcare network: packet inspection, port scanning, a segmented least-privilege firewall redesign and an executive remediation plan. | Firewall design · Vulnerability assessment |
| **Enterprise Threat Modeling** | STRIDE analysis of a complex network, with MITRE ATT&CK mapping and data flow diagrams to find trust boundaries. | STRIDE · MITRE ATT&CK · DFDs |
| **CTI Platform Comparison** | Proof of concept comparing MISP and OpenCTI on STIX/TAXII ingestion, IoC enrichment and ATT&CK mapping at Western Union. | MISP · OpenCTI · STIX/TAXII · Containers |

### How OpenElia works

```mermaid
flowchart LR
    A["roe.json scope gate<br/>fails closed"] --> B["Red agents<br/>recon, exploit, exfil"]
    B --> C["Blue agents<br/>Sigma, LLM triage, hunt, contain"]
    C --> D["Reporter<br/>MITRE heatmap, chain of custody"]
    D -. "coverage delta" .-> B
```

- Offensive modules run in ephemeral, rootless Docker containers with all Linux capabilities dropped.
- Audit entries are chained with HMAC-SHA256, so tampering shows up in the log.
- Blue-team remediation stays in simulation mode until it is explicitly enabled.

## What I work with

| | |
|---|---|
| **Detection and response** | Microsoft Defender XDR · KQL · Sigma · Splunk · ELK |
| **Threat intelligence** | MITRE ATT&CK mapping · STIX/TAXII · MISP · OpenCTI |
| **AI security** | AI-assisted SOC workflows · LLM red teaming · OWASP Top 10 for LLM Applications |
| **Infrastructure** | AWS VPCs · Entra ID · Active Directory · Linux · Python · PowerShell |
| **Certifications** | CompTIA Security+ · CompTIA Network+ · Google Cybersecurity Specialization · NVIDIA Fundamentals of Deep Learning · TryHackMe Pre Security · Linux Command Line |
| **Speaking** | 2025 ACM SIGUCCS Annual Conference presenter |
| **Languages** | Persian · English · Pashto |

## Experience

- **Security Analyst Intern, then Junior Security Analyst**, Metropolitan State University of Denver · 2026 to present
- **Cybersecurity Analyst Intern**, Evolve Security Academy · 2026 to present
- **Junior Network Admin**, Metropolitan State University of Denver · 2025 to 2026, 20 sites and over 800 devices
- **Cyber Threat Intelligence Intern**, Western Union · 2025
- **IT Technician and Help Desk**, Metropolitan State University of Denver · 2022 to 2025

## Find me

- 🌐 Portfolio: [m3tan01.github.io](https://m3tan01.github.io)
- 💼 LinkedIn: [linkedin.com/in/mohammadma](https://www.linkedin.com/in/mohammadma/)
- 🎥 YouTube: [CyberArb](https://www.youtube.com/@CyberArb), step-by-step security tutorials on exploits and packet analysis
