# Jesus Meza — Senior Network Engineer

I build small, reliable network‑automation tools that turn tedious multi‑step changes into repeatable, auditable runs. This page focuses on what the repos do and the time they save in real workflows.

**Socials**

[![GitHub](https://img.shields.io/badge/GitHub-jmeza192-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jmeza192)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jesus%20meza-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jmeza192)

**What I Build**

- **Purpose:** Reduce manual CLI work, enforce verification, and leave an audit trail
- **Approach:** Python + Netmiko, clear `.env` templates, multi‑credential fallback, and CI where it helps

**Projects + Impact**

- **VLAN Changer + CI/CD**
  - Problem: Moving users/devices required ARP/MAC lookups, CDP walks, and careful config/verification on access ports.
  - What it does: Locates ports by IP/MAC, traverses CDP across trunks/port‑channels, applies access/voice VLANs, verifies, saves, and can roll back. Ships with GitHub Actions for pre/post audits and reports.
  - Results: Reconfigured ~200 devices in under 4 hours (saved ~3 days of manual effort). Repeatable runs with logs and artifacts — no manual switch hunting.
  - Code: https://github.com/jmeza192/Vlan_Changer
  - Tech: Python, Netmiko, GitHub Actions

- **Network Toolbox**
  - Problem: Routine fleet tasks (AP discovery, serial collection, TACACS audits, config cleanup) consumed time and were error‑prone.
  - What it does: A set of targeted scripts with `.env` templates per tool. Batch operations against device lists, robust credential fallback, and clear progress/logging.
  - Results: Cuts repetitive CLI steps to a single command; easier to run at scale and hand off to teammates with templates.
  - Code: https://github.com/jmeza192/network-toolbox-public
  - Tech: Python, Netmiko, Pandas, dotenv

- **Wiping Config**
  - Problem: Decommissioning or baseline cleanup required dozens of manual commands per device and was easy to miss items.
  - What it does: Removes SNMP/NTP, banners, logging hosts, TACACS servers/keys, certain local users, legacy TTY settings, and other artifacts; produces clear progress and error logs.
  - Results: Collapses multi‑step per‑device cleanup into one repeatable run, speeding up fleet resets and standardization efforts.
  - Code: https://github.com/jmeza192/network-toolbox-public/tree/main/tools/wiping%20config
  - Tech: Python, Netmiko
  - Note: Destructive by design — intended for controlled cleanup workflows.

- **Personal Website (This Site)**
  - What it does: Quick portfolio with resume download, project summaries, and links.
  - Goal: Give recruiters an at‑a‑glance view of impact and repos.
  - Code: https://github.com/jmeza192/jmeza192.github.io
  - Live: https://jmeza192.github.io

**Why This Matters**

- Turns multi‑hop troubleshooting into a deterministic workflow with verification and optional rollback
- Standardized patterns: environment‑isolated configs, credential fallback, adaptive timing, and pre/post checks
- Produces artifacts (logs/reports) for change records and troubleshooting

**Skills Snapshot**

- **Security/Firewalls:** Palo Alto PA‑series (NGFW, App‑ID, TLS decryption)
- **Switching/Routing:** Cisco Catalyst/NX‑OS, Aruba; OSPF, BGP, EIGRP; EVPN, vPC, LACP; QoS, Multicast
- **Automation/Tooling:** Python, Netmiko, GitHub Actions, EVE‑NG, Proxmox
- **Access/Identity:** ISE/TACACS+, ACLs, NAT, VPN
- **Observability:** SolarWinds, Wireshark

**Tech Stack**

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Juniper](https://img.shields.io/badge/Juniper-84B135?style=for-the-badge&logo=junipernetworks&logoColor=white)
![Aruba](https://img.shields.io/badge/Aruba-ED6F00?style=for-the-badge&logo=aruba&logoColor=white)
![Arista](https://img.shields.io/badge/Arista-003D6B?style=for-the-badge&logoColor=white)
![Palo Alto Networks](https://img.shields.io/badge/Palo%20Alto%20Networks-F37021?style=for-the-badge&logo=palantir&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![SolarWinds](https://img.shields.io/badge/SolarWinds-F2B01A?style=for-the-badge&logo=solarwinds&logoColor=black)
![Infoblox](https://img.shields.io/badge/Infoblox-1C3F94?style=for-the-badge&logo=infoblox&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Cisco ISE](https://img.shields.io/badge/Cisco%20ISE-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Aruba ClearPass](https://img.shields.io/badge/Aruba%20ClearPass-ED6F00?style=for-the-badge&logo=aruba&logoColor=white)

**Links**

- **GitHub:** https://github.com/jmeza192
- **LinkedIn:** https://www.linkedin.com/in/jmeza192
- **Resume (PDF):** ./resume.pdf

If you’d like a quick walkthrough or deeper technical detail on any project, feel free to reach out via LinkedIn.
