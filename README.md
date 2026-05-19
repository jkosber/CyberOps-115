# CyberOps-115 — CSIA 115 Cyber Ops (Cisco CyberOps Associate)

My Spring 2026 coursework at Ivy Tech Kokomo — 8-week section (Jan 18 – Mar 11). Eight modules of the Cisco Networking Academy *CyberOps Associate* curriculum, aimed at the entry-level Security SOC Analyst / Incident Responder track. Ended with the CyberOps Associate Skills Exam (practical) and Certification Practice Exam, both passed. Each course module covers a chunk of Cisco's underlying book modules:

| Course module | Book modules |
| :---  | :--- |
| M01   | 1–2  (Cybersecurity / SOC; Threat actors and defenders) |
| M02   | 3–4  (Windows OS; Linux OS) |
| M03   | 5–10 (Network fundamentals) |
| M04   | 11–12 (Network infrastructure) |
| M05   | 13–17 (Threats and attacks) |
| M06   | 18–23 (Network defense; Cryptography; Endpoint protection) |
| M07   | 24–28 (Protocols and log files; Analyzing security data) |
| M08   | Final + Skills Exam + Certification Practice Exam |

## Tools

- **Wireshark** — packet inspection across modules 3, 4, 6, 7.
- **Cisco Packet Tracer** — `.pka` files for ACL demos, packet-flow ID, NetFlow, multi-source logging.
- **Snort** — IDS and firewall-rule labs (Module 7).
- **Nmap** — reconnaissance (Module 3).
- **OpenSSL** — hashing, encryption / decryption practice (Module 6).
- **MySQL** — attack-reading lab (Module 5).
- **PowerShell + Linux CLI** — Windows and Linux investigative work (Module 2).
- Class-provided Cisco lab VMs.

## Repository layout

```
Module01/  Threat landscape, VM setup, attacker mindset, Windows processes / registry / accounts
Module02/  Windows PowerShell + Task Manager; Linux shell, files, servers, logs, permissions
Module03/  Network fundamentals — traceroute, Wireshark intro, Packet Tracer addressing verify, Nmap, TCP 3-way handshake
Module04/  Application-layer Wireshark (DNS, TCP/UDP, HTTP/HTTPS); packet flow and ACL demos
Module05/  Threats and attacks — DNS investigation, MySQL attack reading, server-log review, NetFlow PT
Module06/  Cryptography + endpoint defense — hashing, OpenSSL, Telnet vs SSH in Wireshark, CA stores
Module07/  Protocols / log analysis — NetFlow PT, Snort rules, regex, PCAP exec extraction, 5-tuple isolation, malware / Windows-host investigation, incident handling
Module08/  Skills Assessment capstone + Skills Exam Report Template (final / practical)
```

## Module walkthrough

- **Module 1 — SOC role, threat landscape, defender mindset.** Top-hacker case study (Activity 1.0.6); lab installing the class VMs (1.1.5); learning the details of attacks (1.2.3); the "becoming a defender" reflection (2.2.5); Windows labs on processes / threads / handles (3.2.11), creating user accounts (3.3.10), and the Identify Running Processes activity (3.0.3). Modules 1–2 Group Exam closed the module.
- **Module 2 — OS-level visibility (Windows + Linux).** Windows PowerShell (3.3.11), Task Manager (3.3.12), system-resource monitoring (3.3.13). Linux side — text files in the CLI (4.2.6), getting familiar with the Linux shell (4.2.7), Linux servers (4.3.4), locating log files (4.4.4), filesystem and permissions (4.5.4). Modules 3–4 Group Exam.
- **Module 3 — Network fundamentals.** Tracing routes (5.1.5), Wireshark introduction (5.3.7), verifying IPv4 / IPv6 addressing in Packet Tracer (`7.2.8.pka` saved), examining Ethernet frames (8.2.8), capturing the TCP 3-way handshake (9.2.6), exploring Nmap (9.3.8).
- **Module 4 — Network infrastructure under inspection.** Wireshark on UDP DNS (10.2.7), TCP / UDP captures side-by-side (10.4.3), HTTP and HTTPS (10.6.7). Packet Tracer labs for packet-flow identification (12.1.9) and ACL demonstration (12.3.4) — both `.pka` files saved. Modules 5–10 + 11–12 Group Exams.
- **Module 5 — Threats and attacks.** "What's Going On" class activity (15.0.3), Packet Tracer logging-of-network-activity (15.2.7), DNS-traffic exploration (17.1.7), reading a MySQL-database attack (17.2.6), server-log analysis (17.2.7). Modules 13–17 Group Exam.
- **Module 6 — Network defense, cryptography, endpoint.** Creating cryptographic codes (21.0.3), hashing (21.1.6), OpenSSL encrypt / decrypt (21.2.10), attacker-tool decrypt for contrast (21.2.11), Telnet vs SSH in Wireshark (21.2.12), certificate authority stores (21.4.7). Modules 18–20 + 21–23 Group Exams.
- **Module 7 — Protocols, log analysis, incident response.** NetFlow implementation (25.3.10) and multi-source logging (25.3.11) in Packet Tracer. Snort + firewall rules (26.1.7). Regular expressions for log triage (27.2.9). Converting data into a universal format (27.1.5). Extracting an executable from a PCAP (27.2.10). HTTP and DNS interpretation to isolate a threat actor (27.2.12). 5-tuple host isolation (27.2.14). Malware-exploit investigation (27.2.15). Investigating an attack against a Windows host (27.2.16). Full incident-handling lab (28.4.13). Modules 24–25 + 26–28 Group Exams.
- **Module 8 — Final exams.** Practice Final Exam, Final Exam, **Skills Exam** (practical) with its report template, plus the Cisco CyberOps Associate **Certification Practice Exam**. `CA v1.0 Skills Assessment.docx` and `SkillsExamReportTemplate.docx` in the repo are from this module.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1 networking foundations.
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals.
- [SVAD-111-Linux-Virtualization](https://github.com/jkosber/SVAD-111-Linux-Virtualization) — official prerequisite for this course.
