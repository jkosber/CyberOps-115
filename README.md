# CyberOps-115 — Cyber Ops (CSIA 115)

My Spring 2026 coursework for **Ivy Tech CSIA 115 — Cyber Ops** at Ivy Tech Kokomo. Eight modules of the Cisco Networking Academy *CyberOps Associate* curriculum, taken as an 8-week section (Jan 18 – Mar 11, 2026). The course is aimed at the entry-level Security SOC Analyst / Incident Responder track and ends with the CyberOps Associate Skills Exam and Certification Practice Exam.

Each course module covers a chunk of Cisco's underlying CyberOps Associate book modules. The mapping (visible from the group-exam titles in my schedule) was:

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

## Course information

| Field            | Detail                                                                                |
| :--------------- | :------------------------------------------------------------------------------------ |
| Course number    | CSIA 115                                                                              |
| Course title     | Cyber Ops                                                                             |
| School / program | Information Technology — Cyber Security / Information Assurance                       |
| Credit hours     | 3                                                                                     |
| Contact hours    | Lecture 2, Lab 2                                                                      |
| Prerequisites    | SVAD 111 — Linux and Virtualization Technologies Fundamentals                         |
| Term             | Spring 2026 — 8-week section, Jan 18 – Mar 11, 2026                                   |
| Curriculum       | Cisco Networking Academy — CyberOps Associate                                         |

## Catalog description

> This course introduces the core security concepts and skills needed to monitor, detect, analyze and respond to cybercrime, cyberespionage, insider threats, advanced persistent threats, regulatory requirements, and other cybersecurity issues facing organizations. It emphasizes the practical application of the skills needed to maintain and ensure security operational readiness of secure networked systems. The skills developed in the curriculum prepares students for a career in the rapidly growing area of cybersecurity operations working in or with a security operations center (SOC) in entry-level job roles such as Security SOC Analyst and Incident Responder.

## What you're supposed to be able to do by the end

1. Explain the role of the Cybersecurity Operations Analyst.
2. Use OS features that support cybersecurity analysis.
3. Explain how network infrastructure operates and classify network attacks.
4. Analyze network protocols and services and use monitoring tools to identify attacks.
5. Prevent malicious access to computer hosts and data.
6. Explain the impact of cryptography on network security monitoring.
7. Investigate and evaluate endpoint vulnerabilities and network security alerts.
8. Use virtual machines to implement, evaluate, and analyze cybersecurity threat events.
9. Analyze network intrusion data to identify compromised hosts and vulnerabilities.
10. Apply incident response models (CSIRT and NIST) to manage security incidents.
11. Understand how a SOC team detects and responds to security incidents and protects the organization's information.
12. Understand how modern organizations are dealing with cybercrime, cyberespionage, insider threats, APTs, regulatory requirements, and other current issues.

## Topical content

Cybersecurity and the Security Operations Center · Protecting the network · Windows operating system · Cryptography and the Public Key Infrastructure · Linux operating system · Network protocols and services · Network infrastructure · Principles of network security · Endpoint security and analysis · Security monitoring · Incident response and handling.

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
CyberOps115/
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

## Outcome

Course completed Spring 2026 — counts toward the Cyber Security & Information Assurance Technical Certificate at Ivy Tech Kokomo. Cisco Networking Academy CyberOps Associate course materials. Final exam, Skills Exam, and Certification Practice Exam passed.

## Related repos

- [Networking-109](https://github.com/jkosber/Networking-109) — CCNA Part 1 networking foundations.
- [CSIA-210-Network-Protocol-Analysis](https://github.com/jkosber/CSIA-210-Network-Protocol-Analysis) — deeper packet-level analysis.
- [IntroToCybersecurity-105](https://github.com/jkosber/IntroToCybersecurity-105) — cybersecurity fundamentals.
- [SVAD-111-Linux-Virtualization](https://github.com/jkosber/SVAD-111-Linux-Virtualization) — official prerequisite for this course.
