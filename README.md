# kuumeunta

Aspiring information security specialist. Currently building hands-on labs in VirtualBox around Linux hardening, network traffic and log analysis.

Interested in: SOC analysis, penetration testing, OSINT, and ML-based anomaly detection in logs.

## Lab track

| # | Lab | What I did | Skills shown |
|---|-----|-----------|--------------|
| 00 | [firewall-lab](https://github.com/kuumeunta/00-firewall-lab) | ufw between two Ubuntu VMs, deny-by-default, SSH | firewall rules, SSH, basic network testing |
| 01 | [ufw-logging-lab](https://github.com/kuumeunta/01-ufw-logging-lab) | Read ufw logs, found blocked SYN packets, filtered multicast noise | log analysis, grep filtering |
| 02 | [wireshark-ufw-traffic-lab](https://github.com/kuumeunta/02-wireshark-ufw-traffic-lab) | Captured ICMP and TCP with closed and open ports | Wireshark, TCP handshake, packet-level view of firewall behavior |
| 03 | [ssh-failed-logins-lab](https://github.com/kuumeunta/03-ssh-failed-logins-lab) | Analyzed failed SSH logins, set up fail2ban | auth log analysis, intrusion prevention |
| 04 | *in progress*: bash log parser | | scripting, automation |

**Planned**: Bruteforce & fail2bans, Windows security basics, Linux hardening basic

**Lab structure**: Goal → Environment → Steps with screenshots → Problems → Conclusions.

**Lab environment**:
All labs run on: Windows 10 host, VirtualBox, two Ubuntu VMs, Host-Only network.
Everything is isolated; no real systems or credentials involved.

## Operating systems

- Daily use: Windows 10, Kali Linux (i3)
- Regular use: Ubuntu (many installations, labs), Windows 11
- Worked with: Windows Server, RED OS
- Limited experience: Astra Linux

## Tools & workflow

- Obsidian: 2+ years of daily use for notes, lab documentation and knowledge base
- [Vault Modules](https://github.com/kuumeunta/Obsidian-Modules): Obsidian plugin for enabling/disabling vault folders as modules.
  Designed by me, built with Claude Code (AI-assisted).

## Infrastructure

- Firewalls & networking: pfSense, MikroTik & Cisco Packet Tracer (both very basic)
- Databases: PostgreSQL
- Imaging & boot media: Clonezilla, Rufus, UltraISO
- In labs: ufw, ssh, fail2ban, Wireshark, journalctl, grep, bash

## Contact

