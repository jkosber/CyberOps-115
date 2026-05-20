# CyberOps-115 — CSIA 115 Cyber Ops (Cisco CyberOps Associate)

My Spring 2026 coursework at Ivy Tech Kokomo — 8-week section (Jan 18 – Mar 11). Eight modules of the Cisco Networking Academy *CyberOps Associate* curriculum, aimed at the entry-level Security SOC Analyst / Incident Responder track. Ended with the CyberOps Associate Skills Exam (practical) and Certification Practice Exam, both passed.

## Tools

- **Wireshark** — packet inspection across modules 3, 4, 6, 7.
- **Cisco Packet Tracer** — `.pka` files for ACL demos, packet-flow ID, NetFlow, multi-source logging.
- **Snort** — IDS and firewall-rule labs (Module 7).
- **Nmap** — reconnaissance (Module 3).
- **OpenSSL** — hashing, encryption / decryption practice (Module 6).
- **MySQL** — attack-reading lab (Module 5).
- **PowerShell + Linux CLI** — Windows and Linux investigative work (Module 2).
- Class-provided Cisco lab VMs.

## Module mapping

Each course module covers a chunk of the underlying Cisco book modules:

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

- **Module 1 — SOC role, threat landscape, defender mindset.** Top-hacker case study; lab installing the class VMs; learning the details of attacks; the "becoming a defender" reflection; Windows labs on processes / threads / handles, creating user accounts, and the Identify Running Processes activity. Modules 1–2 Group Exam wrapped the module.
- **Module 2 — OS-level visibility (Windows + Linux).** Windows PowerShell, Task Manager, system-resource monitoring. Linux side — text files in the CLI, getting familiar with the Linux shell, Linux servers, locating log files, filesystem and permissions. Modules 3–4 Group Exam.
- **Module 3 — Network fundamentals.** Tracing routes, Wireshark introduction, verifying IPv4 / IPv6 addressing in Packet Tracer (`7.2.8.pka` saved), examining Ethernet frames, capturing the TCP 3-way handshake, exploring Nmap.
- **Module 4 — Network infrastructure under inspection.** Wireshark on UDP DNS, TCP / UDP captures side-by-side, HTTP and HTTPS. Packet Tracer labs for packet-flow identification and ACL demonstration — both `.pka` files saved. Modules 5–10 + 11–12 Group Exams.
- **Module 5 — Threats and attacks.** "What's Going On" class activity, Packet Tracer logging-of-network-activity, DNS-traffic exploration, reading a MySQL-database attack, server-log analysis. Modules 13–17 Group Exam.
- **Module 6 — Network defense, cryptography, endpoint.** Creating cryptographic codes, hashing, OpenSSL encrypt / decrypt, attacker-tool decrypt for contrast, Telnet vs SSH in Wireshark, certificate authority stores. Modules 18–20 + 21–23 Group Exams.
- **Module 7 — Protocols, log analysis, incident response.** NetFlow implementation and multi-source logging in Packet Tracer. Snort + firewall rules. Regular expressions for log triage. Converting data into a universal format. Extracting an executable from a PCAP. HTTP and DNS interpretation to isolate a threat actor. 5-tuple host isolation. Malware-exploit investigation. Investigating an attack against a Windows host. Full incident-handling lab. Modules 24–25 + 26–28 Group Exams.
- **Module 8 — Final exams.** Practice Final Exam, Final Exam, **Skills Exam** (practical) with its report template, plus the Cisco CyberOps Associate **Certification Practice Exam**. `CA v1.0 Skills Assessment.docx` and `SkillsExamReportTemplate.docx` in the repo are from this module.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1 networking foundations.
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals.
- [SVAD-111-Linux-Virtualization](https://github.com/jkosber/SVAD-111-Linux-Virtualization) — official prerequisite for this course.
