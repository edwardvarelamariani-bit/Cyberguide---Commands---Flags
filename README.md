# CyberGuide — Commands & FLAGS Reference

> Interactive cybersecurity command reference for SOC analysts, Blue Team and penetration testing students.

![HTML](https://img.shields.io/badge/HTML5-single--file-orange?style=flat-square&logo=html5)
![Coverage](https://img.shields.io/badge/coverage-11%20sections%20·%2060%2B%20commands-blue?style=flat-square)
![Audience](https://img.shields.io/badge/audience-SOC%20%7C%20Blue%20Team%20%7C%20CTF-cyan?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## Overview

This is a self-contained, searchable HTML reference guide consolidating the most relevant Linux, networking, and security commands used in real SOC and penetration testing workflows.

Built as a personal study tool during the **IFCT0109 Certificado de Profesionalidad — Seguridad Informática (Nivel 3)** program, and refined through hands-on practice in a home lab environment running Wazuh SIEM, Docker-based vulnerable targets, and active CTF participation.

**Live demo:** [GitHub Pages link] *(rename to `index.html` and enable Pages to deploy)*

---

## Contents

| # | Section | Tools covered |
|---|---------|---------------|
| 01 | **Linux Base** | `ls`, `find`, `chmod`, `cp/mv/rm`, `ps`, `kill`, `crontab`, `tar` |
| 02 | **Reconnaissance** | `nmap`, `whois`, `dig`, `nslookup`, `host` |
| 03 | **Web Scanning & Fuzzing** | `curl`, `sqlmap`, `ffuf`, Burp Suite |
| 04 | **Log Analysis & Text Processing** | `grep`, `awk`, `sed`, `cut`, `sort`, `uniq`, `wc`, `tail` |
| 05 | **Network Traffic Analysis** | `tcpdump`, `tshark`, `ss`, `netstat`, `zeek` |
| 06 | **Credential Attacks** | `hydra`, `hashcat`, `john the ripper` |
| 07 | **Post-Exploitation** | `ssh` (tunneling, SOCKS proxy), `scp`, Meterpreter |
| 08 | **SOC Tools & Monitoring** | `wazuh-agent`, `systemctl`, `journalctl` |
| 09 | **Forensics & Memory Analysis** | `volatility`, `autopsy`, `strings` |
| 10 | **System Hardening** | `chmod/chown`, `sudo/sudoers`, `ufw`, `firewall-cmd`, `find` |
| 11 | **Bash Scripting** | Variables, conditionals, loops, redirections, pipes |

---

## Features

- **Global search** — filters across all sections in real time (keyboard shortcut: `Ctrl+K`)
- **Tab navigation** — organized by operational context (recon, SOC, forensics, etc.)
- **Collapsible cards** — flags and examples expandable on demand
- **One-click copy** — every command example has a copy button
- **Sidebar** — quick jump to any command within the active section
- **Context badges** — commands labeled as SOC, RED TEAM, or LINUX for quick orientation
- **Single HTML file** — no dependencies, no build step, works offline

---

## Usage

```bash
# Clone
git clone https://github.com/edwardvarelamariani-bit/cyberguide-commands-flags.git

# Open locally — no server required
open CyberGuide_Comandos_FLAGS.html
```

Or deploy to GitHub Pages:
1. Rename the file to `index.html`
2. Push to the `main` branch
3. Enable Pages in repository settings → Source: `main` / `root`

---

## Lab Context

This guide was developed alongside a home cybersecurity lab built on an Apple M1 (ARM64) host running:

- **Wazuh 4.x** — SIEM with custom detection rules (SSH brute force, Nmap scans, SQLi)
- **Docker** — DVWA, WebGoat, OWASP Juice Shop, Nagios
- **Kali Linux / Parrot OS** — attack VMs via UTM
- **AI SOC agents** — Python scripts querying Wazuh API + Ollama (llama3.2) for automated report generation

Related repositories:
- [`Laboratorio-Ciber`](https://github.com/edwardvarelamariani-bit/Laboratorio-Ciber) — full lab setup and documentation
- [`Wazuh-arm64-lab`](https://github.com/edwardvarelamariani-bit/Wazuh-arm64-lab) — Wazuh native installation on ARM64
- [`MCP-Packet-Tracer`](https://github.com/edwardvarelamariani-bit/MCP-Packet-Tracer) — Claude + Cisco Packet Tracer integration

---

## Author

**Edward Varela Mariani**
Cybersecurity student · Junior SOC / Blue Team analyst (target role)
IFCT0109 Nivel 3 — Alicante, Spain · 2026

[GitHub](https://github.com/edwardvarelamariani-bit) · [LinkedIn](#)

---

## License

MIT — free to use, adapt and share with attribution.
