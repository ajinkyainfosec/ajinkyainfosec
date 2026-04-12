<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:003322,100:00FF88&height=180&section=header&text=Ajinkya%20Bhosale&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=45&desc=Cybersecurity%20Professional%20%E2%80%A2%20Penetration%20Tester%20%E2%80%A2%20Secure%20Developer&descAlignY=70&descSize=16&descColor=00FF88" width="100%"/>

</div>

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3500&pause=1200&color=00FF88&center=true&vCenter=true&width=600&lines=Security+Researcher+%7C+SOC+Analyst;Penetration+Testing+%7C+Threat+Detection;Building+Defenses+%7C+Breaking+Weaknesses;MITRE+ATT%26CK+%7C+SIEM+%7C+Incident+Response)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajinkya--bhosale)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/aj1nky0)
[![Portfolio](https://img.shields.io/badge/Portfolio-00FF88?style=flat-square&logo=Firefox-Browser&logoColor=000)](https://learnwithajinkya.dev)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/Ajinkya_offical)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bhosaleajinkya2205@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ajinkyainfosec&color=00FF88&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/ajinkyainfosec?style=flat-square&color=00FF88&label=Followers)

</div>

---

## About Me

I'm a **Cybersecurity Professional and Full-Stack Developer** based in Pune, India, pursuing my B.E. in Computer Science & Engineering at Sinhgad Institute of Technology & Science (CGPA: 8.07).

My work sits at the intersection of **offense and defense** — I study how attackers think, then build systems that stop them. From deploying production-grade intrusion detection systems to competing in CTF challenges, I'm driven by one goal: understanding and eliminating risk before adversaries exploit it.

- 🎯 **Focus:** Blue Team Operations ·Penetration Testing · SIEM · Threat Detection 
- 🔭 **Exploring:** Cloud Security (AWS/Azure) · AI-driven Threat Detection · Mobile Pentesting
- 🏆 **Active on TryHackMe** — consistently solving real-world attack/defense scenarios
- 🤝 **Open to:** Collaborations · Bug Bounty · Security Research · CTF Teams

---

## Core Competencies

<table>
<tr>
<td width="50%" valign="top">

**🔴 Offensive Security**
- Web Application Penetration Testing (OWASP Top 10)
- Network Reconnaissance & Exploitation
- Vulnerability Assessment & Reporting
- Social Engineering Awareness
- CTF Challenges & Writeups

</td>
<td width="50%" valign="top">

**🔵 Defensive Security**
- SIEM Implementation (Wazuh, Splunk)
- Host-Based Intrusion Detection
- Incident Response & Alert Triage
- File Integrity Monitoring (FIM)
- MITRE ATT&CK Framework Mapping

</td>
</tr>
<tr>
<td width="50%" valign="top">

**💻 Development**
- Secure Application Architecture
- REST API Development (FastAPI, Flask)
- Frontend Engineering (React, Tailwind)
- Security Tool Automation (Python, Bash)
- Containerized Deployment (Docker)

</td>
<td width="50%" valign="top">

**🔬 Research & Intelligence**
- OSINT & Threat Intelligence Gathering
- Sigma Rule Authoring
- Log Analysis & Forensics
- Honeypot Design & Attacker Profiling
- Security Automation Scripting

</td>
</tr>
</table>

---

## Featured Projects

### 🔐 Host-Based Intrusion Detection System (HIDS)
**[View Repository →](https://github.com/ajinkyainfosec/Host-based-intrusion-detection)**

A production-grade, real-time HIDS built entirely from scratch — combining a **Rust kernel agent**, **Python/FastAPI backend**, and a **14-tab live SOC dashboard**. Detects real attacks in under 1 second with 80% detection accuracy across diverse attack scenarios.

| Component | Technology | Purpose |
|-----------|-----------|---------|
| Agent | Rust + Linux `inotify` | Sub-second file change detection |
| Backend | Python + FastAPI + Redis | Alert processing & WebSocket streaming |
| Storage | PostgreSQL + Elasticsearch | Structured logs & full-text search |
| Dashboard | JavaScript + D3.js + Chart.js | 14-tab live SOC interface |
| Deployment | Docker Compose + Nginx | 6-container production stack |

**Detection Coverage:**
SSH brute force · Reverse shells · Rootkit indicators · Privilege escalation · C2 beacon patterns · Cron-based persistence · File integrity violations

**Key Highlights:**
- ⚡ `inotify`-based FIM detects changes in **< 1 second** (vs 30s polling alternatives)
- 🗺️ **17 Sigma rules** mapped across **8 MITRE ATT&CK tactics**
- 📊 Kill Chain Timeline — visualizes attack progression stage by stage
- 🕸️ D3.js Threat Correlation Graph — links alerts, hosts, IPs, and tactics
- 🗂️ Kanban Triage Board — NEW → INVESTIGATING → CONTAINED → CLOSED
- 🖱️ One-Click Response — isolate host, kill process, block IP, quarantine file
- 📄 PDF Incident Reports with full MITRE mapping and risk scoring

`Rust` `Python` `FastAPI` `PostgreSQL` `Redis` `Elasticsearch` `Docker` `Nginx` `D3.js` `WebSocket` `MITRE ATT&CK` `Sigma Rules` `Prometheus`

---

### 🍯 Python-Based Honeypot
**[View Repository →](https://github.com/ajinkyainfosec/basic-honeypot)**

A lightweight, multi-service honeypot for capturing and analyzing real attacker TTPs. Designed for threat intelligence collection and defensive research.

- Simulates SSH, FTP, HTTP, and HTTPS services simultaneously via socket programming
- Behavioral fingerprinting and IP geolocation tracking per session
- Structured logging in JSON/CSV format — SIEM-ready output
- Realistic server response mimicry to maximize attacker engagement time

`Python` `Socket Programming` `Multithreading` `JSON` `CSV`

---

### 📊 Wazuh SIEM & Vulnerability Monitoring Lab
**[View Profile →](https://github.com/ajinkyainfosec)**

Enterprise-grade SIEM deployment for comprehensive threat visibility across endpoints.

- Centralized log collection and correlation across multiple Linux agents
- File Integrity Monitoring with real-time alerting
- Automated vulnerability detection and CVE mapping
- Custom alert rules for environment-specific threat detection

`Wazuh` `Elasticsearch` `Linux` `Log Analysis` `FIM`

---

### 🔑 Keylogger — Educational Security Research
**[View Repository →](https://github.com/ajinkyainfosec/keylogger)**

Built for ethical research and defensive awareness. Demonstrates keystroke capture mechanisms used in real-world malware — understanding attacker tooling to build better defenses.

`Python` · *For authorized, educational use only*

---

## Technology Stack

<div align="center">

**Security Tools**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burp-suite&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-00ADEF?style=flat-square&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frameworks & Infrastructure**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

</div>

---

## GitHub Statistics

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=ajinkyainfosec&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=00FF88&icon_color=00FF88&text_color=c9d1d9&count_private=true"/>
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ajinkyainfosec&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=00FF88&text_color=c9d1d9"/>

</div>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=ajinkyainfosec&theme=dark&hide_border=true&background=0d1117&ring=00FF88&fire=00FF88&currStreakLabel=00FF88&sideLabels=00FF88&dates=c9d1d9"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ajinkyainfosec&theme=react-dark&hide_border=true&area=true&bg_color=0d1117&color=00FF88&line=00FF88&point=ffffff" width="100%"/>

</div>

---

## Learning Roadmap

```
SKILL                        PROGRESS              STATUS
──────────────────────────────────────────────────────────────────────
Network Security          ████████████████████   Mastered
Web App Security          ████████████████████   Mastered
SIEM & SOC Operations     ██████████████████░░   Advanced
Penetration Testing       ████████████████░░░░   Advanced
Exploit Development       ████████████░░░░░░░░   In Progress  ←
Malware Analysis          ████████░░░░░░░░░░░░   In Progress  ←
Cloud Security (AWS/GCP)  ██████░░░░░░░░░░░░░░   Exploring
Mobile App Pentesting     ████░░░░░░░░░░░░░░░░   Planned
IoT / Firmware Analysis   ███░░░░░░░░░░░░░░░░░   Planned
Security Architecture     ██░░░░░░░░░░░░░░░░░░   Planned
```

**Certification Pathway:**
- 🎯 eJPT → OSCP (active pursuit)
- 🏆 TryHackMe SOC Analyst & Jr. Penetration Tester paths
- ☁️ AWS Security Specialty (planned)
- 🔍 Google Cybersecurity Certificate

---

## Let's Connect

<div align="center">

I'm always open to meaningful conversations about security research, collaboration on open-source tools, or discussing the latest threat landscape.

<br/>

| Platform | Link |
|----------|------|
| 📧 **Email** | [bhosaleajinkya2205@gmail.com](mailto:bhosaleajinkya2205@gmail.com) |
| 💼 **LinkedIn** | [linkedin.com/in/ajinkya--bhosale](https://www.linkedin.com/in/ajinkya--bhosale) |
| 🌐 **Portfolio** | [learnwithajinkya.dev](https://learnwithajinkya.dev) |
| 🏆 **TryHackMe** | [tryhackme.com/p/aj1nky0](https://tryhackme.com/p/aj1nky0) |
| 🐦 **Twitter / X** | [@Ajinkya_offical](https://x.com/Ajinkya_offical) |
| 📍 **Location** | Pune, Maharashtra, India |

<br/>

> *"Security is not a product, but a process."* — Bruce Schneier

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF88,100:003322&height=120&section=footer&animation=fadeIn" width="100%"/>
</div>
