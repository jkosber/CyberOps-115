# CyberOps-115 — Cisco CyberOps Associate

My Spring 2026 coursework for **Ivy Tech CSIA 115 / Cisco Networking Academy: CyberOps Associate** at Ivy Tech Kokomo. Eight modules walking through the Cisco CyberOps Associate curriculum — security operations fundamentals, attack analysis, defense methodology, and hands-on SIEM / IDS work with Wireshark, Security Onion, and Snort.

## What's covered

The course moves from "what does a SOC analyst actually do" through OS-level visibility (Windows + Linux), into protocol analysis (Wireshark, traceroute, Nmap), then into the SOC-style content — log review, alert triage, cryptography in practice, NetFlow, Snort rules, and full incident-handling workflows that extract executables from PCAPs, isolate compromised hosts via 5-tuple, and walk through malware investigations on a Windows host.

## Tools used across the modules

- **Security Onion** — the SIEM platform; log and alert analysis exercises.
- **Wireshark** — packet inspection for handshakes, frames, and application-layer traffic.
- **Cisco Packet Tracer** — `.pka` files for ACL demos, packet-flow ID, NetFlow, multi-source logging.
- **Snort** — IDS and firewall-rule labs.
- **Nmap** — reconnaissance.
- **OpenSSL** — hashing, encrypt/decrypt practice.
- **PowerShell + Linux CLI** — host-side investigation utilities.

## Repository layout

```
CyberOps115/
  Module01/  Threat landscape, VM setup, attacker mindset, Windows processes / registry / accounts
  Module02/  Windows PowerShell + Task Manager; Linux shell, files, servers, logs, permissions
  Module03/  Network basics — traceroute, Wireshark intro, Packet Tracer addressing verify, Nmap, TCP 3-way handshake
  Module04/  Application-layer Wireshark (DNS, TCP/UDP, HTTP/HTTPS); packet flow and ACL demos
  Module05/  SOC visibility — logging, DNS investigation, MySQL attack reading, server-log review
  Module06/  Cryptography — hashing, OpenSSL, Telnet vs SSH in Wireshark, Certificate Authority stores
  Module07/  NetFlow, Snort rules, data normalization, PCAP exec extraction, 5-tuple isolation, malware / Windows-host investigation, incident handling
  Module08/  CA v1.0 Skills Assessment capstone + Skills Exam Report Template
```

## Module walkthrough

- **Module 1 — Threat landscape and the defender mindset.** Top-hacker case study; lab installing the class VMs; learning the details of attacks; the "becoming a defender" reflection; Windows labs on processes / threads / handles, the registry, and user accounts.
- **Module 2 — OS-level visibility for SOC analysts.** Windows PowerShell, Task Manager, and system-resource monitoring labs. Linux CLI side — text files in the shell, exploring the shell itself, Linux servers, locating log files, navigating the filesystem with permissions.
- **Module 3 — Network analysis basics.** Tracing routes, first Wireshark intro lab, verifying IPv4 / IPv6 addressing in Packet Tracer (`.pka` saved), examining Ethernet frames, capturing the TCP 3-way handshake, exploring Nmap.
- **Module 4 — Application-layer protocols under inspection.** Wireshark labs on DNS over UDP, comparing TCP/UDP captures, HTTP and HTTPS traffic. Packet Tracer labs identifying packet flow and demonstrating ACL effects.
- **Module 5 — SOC operations and log analysis.** A "what's going on" class activity, Packet Tracer logging-of-network-activity lab, exploring DNS traffic, reading a MySQL-database attack, and server-log review.
- **Module 6 — Cryptography in practice.** Hashing lab, OpenSSL encrypt/decrypt, an attacker-tool decrypt for contrast, Telnet vs SSH side-by-side in Wireshark, inspecting certificate authority stores, plus a class activity on creating cryptographic codes.
- **Module 7 — Incident response and threat hunting.** NetFlow implementation and multi-source logging in Packet Tracer. Snort + firewall rules. Regex for log triage. Extracting an executable from a PCAP. HTTP and DNS interpretation to isolate a threat actor. 5-tuple host isolation. Malware-exploit investigation. Investigating an attack on a Windows host. Full incident-handling lab.
- **Module 8 — Skills Assessment capstone.** CA v1.0 Skills Assessment and the matching Skills Exam Report Template.

## Outcome

Course completed Spring 2026 — counts toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Cisco Networking Academy CyberOps Associate course materials.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1 network foundations that the SOC work here assumes.
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals.
