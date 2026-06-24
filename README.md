# Raad — Cybersecurity Researcher

BSc Cybersecurity student (penultimate year) at Asia Pacific University, Kuala Lumpur.
Focused on reverse engineering, malware analysis, and IoT/hardware security.
Currently in a cybersecurity R&D internship in Qatar — working on malware analysis,
hardware research, and CTF. Targeting a junior security research or analyst role.

---

## Currently Working On

- Developing a C# deobfuscator for heavily obfuscated .NET malware samples
- IoT hardware security research targeting embedded debug interfaces
- Responsible disclosure pipeline for discovered vulnerabilities

---

## Focus Areas

- **Reverse Engineering** — .NET deobfuscation, control flow flattening, dnlib, Ghidra, dnSpy
- **Malware Analysis** — static analysis, unpacking, FLARE VM, AgentTesla family
- **IoT & Hardware Security** — UART extraction, firmware dumping, SquashFS, RF research
- **Binary Exploitation** — GDB/pwndbg, HackTheBox, pwn.college
- **CTF** — active competitor, top placements at APU level

---

## Tools & Skills

| Category | Tools |
|---|---|
| RE / Analysis | Ghidra, dnSpy, dnlib, x64dbg, FLARE VM |
| Hardware | CH341A, UART, Logic Analyzer, ESP32, nRF24 |
| Scripting | Python, C#, Bash |
| Networking | Wireshark, Nmap, Burp Suite |
| Systems | Arch Linux, Windows, QEMU |

---

## Certifications

- Cisco SRE
- Red Hat System Administration (RH124 / RH134)
- CompTIA Sec+ *(in progress)*
- PNPT — TCM Security *(in progress)*

---

## Featured Work

> Full writeups at **[atank.vercel.app](https://atank.vercel.app)**

**AgentTesla .NET Deobfuscator**
Built a C# deobfuscator from scratch using dnlib to reverse heavily obfuscated .NET malware.
Implemented block-map extraction to defeat control flow flattening — no existing tooling handled this sample.

**Jooan JA-A10 IoT Camera Research**
Full hardware teardown: UART extraction, firmware dump via CH341A, SquashFS filesystem analysis,
RTSP stream access, and discovery of an undocumented debug CLI on the SSV6256P Wi-Fi chip exposing
RF calibration commands and raw memory read/write primitives.

**APU OTP Rate-Limit Vulnerability**
Identified and responsibly disclosed a rate-limiting flaw on a GraphQL/AWS AppSync attendance endpoint.
No account lockout, no throttling — full brute-force surface. Rated CVSS 7.1 High.

---

## Stats

![R3dTheFirst's GitHub Stats](https://github-readme-stats.vercel.app/api?username=R3dTheFirst&show_icons=true&theme=dark&hide_border=true)

---

## Contact

**Portfolio:** [atank.vercel.app](https://atank.vercel.app)
**Discord:** r3dthefirst
