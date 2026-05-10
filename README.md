<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&size=36&color=58A6FF&center=true&vCenter=true&width=600&lines=Noah+Barrett&duration=1500&repeat=false&hideCursor=true" alt="Noah Barrett" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&duration=2800&pause=900&color=7EE787&center=true&vCenter=true&width=800&size=22&lines=M365+Incident+Response;BEC+Investigation+Methodology;Identity+%26+Email+Security;Build+it+to+learn+it" alt="Typing SVG" />
</p>

```bash
~$ whoami
Senior Technician · Saint Paul, MN

~$ focus
Defensive ops: M365 IR · Phishing · BEC · Identity & Email Security
Lab work: Three-tier AD · Detection Engineering · IR Tooling

~$ currently-building
kerflegal-lab — production-shaped AD, three-tier admin model

~$ status
Open to conversations on defensive security, IR, and lab work. Reach out anytime.
```

📍 Saint Paul, MN | [LinkedIn](https://www.linkedin.com/in/-noah-barrett-/) | CompTIA Security+, Network+, A+

## Currently building

<p align="center">
  <img src="https://raw.githubusercontent.com/ncbarrett90/kerflegal-lab/main/diagrams/logical-topology.drawio.png" width="600" alt="kerflegal-lab logical topology" />
</p>

**[kerflegal-lab](https://github.com/ncbarrett90/kerflegal-lab)** is a production-shaped Active Directory environment built on Microsoft's three-tier administrative model. Six segmented network zones with default-deny between them. Architectural decisions documented as ADRs before implementation.

**Architecture:**
- Three-tier administrative model (Tier 0 forest infrastructure, Tier 1 servers, Tier 2 endpoints)
- Per-tier privileged access workstations (PAWs)
- Six segmented network zones with default-deny posture
- Dedicated PAW hypervisor
- Proxmox Backup Server classified as tier 0
- Proxmox VE cluster with replication

**Documented artifacts:**
- [17 Architecture Decision Records](https://github.com/ncbarrett90/kerflegal-lab/tree/main/decisions) covering tiering, segmentation, naming, and backup architecture
- [Build log](https://github.com/ncbarrett90/kerflegal-lab/tree/main/build-log) with phase-by-phase narrative writeups
- [Procedures](https://github.com/ncbarrett90/kerflegal-lab/tree/main/procedures) with per-device runbooks ordered by execution sequence
- [Network design](https://github.com/ncbarrett90/kerflegal-lab/tree/main/design) including IP and VLAN scheme

**Stack:** OPNsense · Proxmox VE · Proxmox Backup Server · Wazuh · Windows Server · AD DS · AD CS

## Practicing in production

Day-to-day Microsoft 365 incident response in production tenants. Phishing triage, BEC investigation, account takeover containment. Full work context on [LinkedIn](https://www.linkedin.com/in/-noah-barrett-/).

## Other repos

- **[cybersecurity-lab](https://github.com/ncbarrett90/cybersecurity-lab)** (retired). 8 modules of documented home lab work covering OPNsense, segmented VLANs, Proxmox VE and PBS, Active Directory, Ubuntu hardening, and Wazuh SIEM/EDR deployment with detection engineering.
- **[wireshark-analysis](https://github.com/ncbarrett90/wireshark-analysis)**. Packet analysis labs in an enterprise-inspired home network.

## Focus areas

- Microsoft 365 incident response
- Identity and access management (Entra ID, Active Directory)
- Email security (SPF, DKIM, DMARC, BEC investigation methodology)
- Detection rule design and security tooling
- PowerShell-driven IR tooling
