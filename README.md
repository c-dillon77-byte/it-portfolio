# Charles Dillon: IT Portfolio

![CI](https://github.com/c-dillon77-byte/it-portfolio/actions/workflows/ci.yml/badge.svg)

**Cybersecurity student looking for entry-level roles in IT support, networking and security · Raleigh, NC**

I'm working toward a B.S. in Cybersecurity at ECPI University (Raleigh, NC), expected February 2027. I learn
by building: an enterprise-style Windows home lab, AWS infrastructure written as code, and Python tools
that solve everyday business problems. This page links everything in one place.

<!-- TODO (Chip): optional 1–2 sentences about what kind of role/team you want and your availability. -->

---

## 📁 Projects

| Project | What it shows | Status |
|---|---|---|
| [networking-labs](https://github.com/c-dillon77-byte/networking-labs) | Python networking tools: subnet calculator, ping/port sweep, Cisco config backup (netmiko), show-command parser, each with tests and CI | ✅ Complete (4 of 4 tools) |
| [cybersecurity-project](https://github.com/c-dillon77-byte/cybersecurity-project) | Defensive security tools: auth log analyzer, password policy auditor, nmap vulnerability scan reporter | 🟢 In progress (2 of 3 tools complete, 1 in review) |
| [HomeLab](https://github.com/c-dillon77-byte/HomeLab) | Enterprise-style lab: Hyper-V, two Windows Server domain controllers, AD, DNS, DHCP failover, Group Policy, file shares, OPNsense firewall | 🟢 In progress |
| [my_restaurant.ai](https://github.com/c-dillon77-byte/my_restaurant.ai) | Python sales forecasting (pandas, optional PyTorch) with tests and CI, built around real restaurant operations needs | 🟢 In progress |
| [My_Python](https://github.com/c-dillon77-byte/My_Python) | Python command-line tools: cash register/receipt printer, food cost (COGS) calculator, scientific calculator | 🟢 In progress |

### 🧰 Tools

Each tool has its own README, sample data and tests, and runs in CI.

| Tool | What it does | Status |
|---|---|---|
| [subnet-calculator](https://github.com/c-dillon77-byte/networking-labs/tree/main/subnet-calculator) | IPv4 subnetting and VLSM planning: network/broadcast, host ranges, CIDR ↔ mask, JSON output | ✅ Complete |
| [ping-port-sweep](https://github.com/c-dillon77-byte/networking-labs/tree/main/ping-port-sweep) | Host discovery and TCP connect port scanning for lab subnets, with timeouts, concurrency and safety limits | ✅ Complete |
| [config-backup](https://github.com/c-dillon77-byte/networking-labs/tree/main/config-backup) | Cisco running-config backups over SSH (netmiko), with timestamped files and diffs against the previous backup | ✅ Complete |
| [show-parser](https://github.com/c-dillon77-byte/networking-labs/tree/main/show-parser) | Parses Cisco IOS `show` output (interfaces, VLANs, routes, CDP/LLDP, MAC table) into tables, JSON or CSV | ✅ Complete |
| [log-analyzer](https://github.com/c-dillon77-byte/cybersecurity-project/tree/main/log-analyzer) | Linux SSH/sudo auth log analysis: brute force, password spraying and new-IP logins, with MITRE ATT&CK IDs | ✅ Complete |
| [password-auditor](https://github.com/c-dillon77-byte/cybersecurity-project/tree/main/password-auditor) | Password policy audit: common-password list, optional HIBP k-anonymity check, masked reports | ✅ Complete |
| [vuln-scan-report](https://github.com/c-dillon77-byte/cybersecurity-project/pull/3) | Turns nmap XML into HTML/Markdown/JSON/CSV risk reports with editable rules and scan-to-scan diffs | 🔵 In review |

---

## 🛠️ Skills (as shown in my repositories)

| Area | Evidence |
|---|---|
| **Windows Server & Active Directory** | Redundant domain controllers, DNS replication, DHCP failover, Group Policy (drive mapping), SMB file shares ([HomeLab](https://github.com/c-dillon77-byte/HomeLab)) |
| **Networking & firewalls** | OPNsense firewall/gateway for an isolated lab network (10.10.10.0/24) ([HomeLab](https://github.com/c-dillon77-byte/HomeLab)) |
| **Virtualization** | Hyper-V hosting the lab's servers, client and Linux VMs ([HomeLab](https://github.com/c-dillon77-byte/HomeLab)) |
| **Cloud / infrastructure as code** | AWS CloudFormation templates from coursework, e.g. an S3 static-website template ([S3](https://github.com/c-dillon77-byte/S3)) |
| **Python** | CLI tools, data processing with pandas, a small PyTorch model, pytest tests and GitHub Actions CI ([my_restaurant.ai](https://github.com/c-dillon77-byte/my_restaurant.ai), [My_Python](https://github.com/c-dillon77-byte/My_Python)) |

---

## 🎓 Education & certifications

**Education**
- **B.S. in Cybersecurity**, ECPI University (Raleigh, NC), expected February 2027
- **A.S. in Cybersecurity**, ECPI University (Raleigh, NC), completed April 2025

**Certifications**
- CompTIA Security+ (in progress)
- EC-Council CEH v13 (in progress)

---

## 📫 Contact

- LinkedIn: [linkedin.com/in/charlesdillon](https://www.linkedin.com/in/charlesdillon)
- Email: [charlesdillon77@gmail.com](mailto:charlesdillon77@gmail.com)
- Resume: [Charles_Dillon_Resume.pdf](resume/Charles_Dillon_Resume.pdf)

---

<sub>Each repository has its own README with setup instructions. Code is MIT licensed unless noted otherwise.</sub>
