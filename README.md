# CyberOps-115 — Cisco CyberOps Associate

Coursework for **Ivy Tech CSIA 115 / Cisco Networking Academy: CyberOps Associate**, completed Spring 2026 at Ivy Tech Kokomo. Eight modules of Cisco CyberOps Associate curriculum covering security operations fundamentals, attack analysis, defense methodology, and hands-on SIEM / IDS exposure through Wireshark, Security Onion, and Snort.

## Topics covered

- Cybersecurity overview and the threat landscape
- Windows and Linux operating systems from a SOC analyst's perspective
- Network protocols, IP addressing, and connectivity verification under inspection
- Ethernet, ARP, and packet-flow analysis
- Transport-layer behavior and common application protocols
- Network security infrastructure and access control
- Attackers, tools, and common attack techniques
- Foundations of cyber defense
- Threat intelligence concepts
- Cryptography — hashing, symmetric encryption (OpenSSL), TLS vs Telnet, certificate authority stores
- SIEM and log/alert analysis (Security Onion)
- Endpoint protection concepts
- Intrusion detection — Snort and firewall rule analysis
- Investigative workflows — extracting executables from PCAPs, 5-tuple host isolation, malware exploit analysis, Windows host compromise investigation, incident handling

## Tools and technologies

- **Security Onion** — SIEM platform; log/alert analysis exercises
- **Wireshark** — packet inspection for handshake, frame, and application-layer analysis
- **Cisco Packet Tracer** — `.pka` simulations for ACL demonstration, packet flow, NetFlow, logging from multiple sources
- **Snort** — IDS rule and firewall rule labs
- **Nmap** — reconnaissance and discovery
- **OpenSSL** — practical encryption / decryption / hashing
- **PowerShell, Linux CLI** — host investigation utilities

## Repository layout

```
CyberOps115/
  Module01/  Threat landscape, VM setup, attacker mindset, Windows processes / registry / accounts
  Module02/  Windows PowerShell + Task Manager; Linux shell, files, servers, logs, permissions
  Module03/  Network basics — traceroute, Wireshark intro, Packet Tracer addressing verify, Nmap, TCP 3-way handshake
  Module04/  Application-layer Wireshark (DNS, TCP/UDP, HTTP/HTTPS); packet flow and ACL demonstrations
  Module05/  SOC visibility — logging, DNS investigation, MySQL attack reading, server-log review
  Module06/  Cryptography — hashing, OpenSSL, Telnet vs SSH in Wireshark, Certificate Authority stores
  Module07/  NetFlow, Snort rules, data normalization, PCAP exec extraction, 5-tuple isolation, malware / Windows-host investigation, incident handling
  Module08/  CA v1.0 Skills Assessment (capstone) and Skills Exam Report Template
```

## Module guide

- **Module 1 — Threat landscape and the defender mindset.** Top-hacker case study, virtual-lab installation, learning the details of attacks, "becoming a defender" reflection, plus Windows process/thread/handle, registry, and user-account labs.
- **Module 2 — OS visibility for SOC analysts.** Windows PowerShell, Task Manager, and system-resource monitoring labs; Linux CLI / text-file / server / log-file / filesystem-permission labs.
- **Module 3 — Network analysis basics.** Tracing a route, Wireshark introduction, IPv4 / IPv6 addressing verification in Packet Tracer (`.pka` included), Ethernet frame inspection, TCP 3-way handshake capture, and the first Nmap exploration.
- **Module 4 — Application-layer protocol analysis.** Wireshark labs on DNS over UDP, TCP/UDP comparison, and HTTP/HTTPS traffic; Packet Tracer labs identifying packet flow and demonstrating ACL effects (`.pka` included).
- **Module 5 — SOC operations and log analysis.** "What's Going On" class activity, Packet Tracer logging-of-network-activity lab, DNS-traffic exploration, MySQL-database attack reading, and server-log analysis labs.
- **Module 6 — Cryptography in practice.** Hashing lab, OpenSSL encrypt/decrypt and attacker-tool comparisons, Telnet vs SSH in Wireshark, certificate authority store inspection, plus a class activity creating cryptographic codes.
- **Module 7 — Incident response and threat hunting.** NetFlow implementation and multi-source logging in Packet Tracer; Snort + firewall rules; regular expressions for log triage; extracting executables from PCAPs; HTTP and DNS interpretation to isolate threat actors; 5-tuple host isolation; malware-exploit investigation; investigating an attack against a Windows host; full incident-handling lab.
- **Module 8 — Skills Assessment capstone.** CA v1.0 Skills Assessment and matching Skills Exam Report Template.

## Status

Course completed Spring 2026 — counted toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Cisco Networking Academy CyberOps Associate course materials.

## Related

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1, network foundations
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals context
