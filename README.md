<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:00ff41&height=190&section=header&text=UMANG%20MISHRA&fontColor=00ff41&fontSize=52&fontAlignY=38&desc=Security%20Researcher%20%7C%20Bug%20Bounty%20Hunter%20%7C%20Attack%20Surface%20Builder&descSize=15&descAlignY=60&descColor=c9d1d9" width="100%" />

<a href="https://github.com/umang-mishra23">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=%24+whoami;umang%40kali%3A~%23+subfinder+-d+target.com+%7C+httpx;Finding+IDORs%2C+XSS+%26+auth+bypasses;Building+tools+that+map+the+attack+surface;Top+2%25+on+TryHackMe" alt="Typing SVG" />
</a>

![Visitors](https://komarev.com/ghpvc/?username=umang-mishra23&color=00ff41&style=flat-square&label=VISITORS)
![Followers](https://img.shields.io/github/followers/umang-mishra23?style=flat-square&color=00ff41&labelColor=0d1117)
![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_2%25-00ff41?style=flat-square&labelColor=0d1117&logo=tryhackme&logoColor=white)

</div>

---

## `~/whoami`

```bash
umang@kali:~$ cat profile.txt

  Name        : Umang Mishra
  Role        : Security Researcher & Bug Bounty Hunter (HackerOne, Intigriti)
  Education   : B.Tech CSE @ Lovely Professional University (2023 - 2027)
  Focus       : VAPT | Attack Surface Management | Recon | Web & API Security
  Interests   : Threat Intelligence, OSINT, Detection Engineering
  Building    : AttackGrid, an enterprise ASM platform
  Writing     : Security walkthroughs on Medium
  Status      : 100+ web app assessments | 10+ valid vulns disclosed
```

---

## `~/featured-projects`

### [AttackGrid](https://github.com/umang-mishra23/Attack-Surface-Management-Platform): Enterprise Attack Surface Management Platform

A cloud-native ASM platform with distributed workers for scalable, asynchronous security scanning. It covers asset discovery, technology fingerprinting and vulnerability assessment, with multi-tenant risk scoring and executive reporting.

```mermaid
flowchart LR
    A[Target Domain] --> B[SubMerge<br/>Subdomain Recon]
    B --> C[HTTPX<br/>Live Hosts]
    C --> D[Nmap<br/>Ports & Services]
    D --> E[WhatWeb<br/>Tech Fingerprint]
    E --> F[Nuclei<br/>Vuln Scan]
    F --> G[(PostgreSQL<br/>Results & History)]
    G --> H[Risk Scoring<br/>& Reports]
    I[Redis Streams<br/>Job Queue] -. distributes jobs .-> B
    H --> J[React Dashboard<br/>Live WebSocket Progress]
```

- Redis Streams job queues with worker heartbeat monitoring and retry/crash recovery
- Real-time scan progress over WebSockets
- Horizontally scalable worker deployment

![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=00ff41)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=flat-square&logo=springboot&logoColor=00ff41)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=00ff41)
![Redis](https://img.shields.io/badge/Redis_Streams-0d1117?style=flat-square&logo=redis&logoColor=00ff41)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=00ff41)
![MinIO](https://img.shields.io/badge/MinIO-0d1117?style=flat-square&logo=minio&logoColor=00ff41)

### [SubMerge](https://github.com/umang-mishra23/SubMerge): High-Performance Subdomain Recon Engine

Aggregates multiple passive enumeration tools into one unified asset-discovery pipeline, with parallel execution, timeout handling, de-duplication, and DNSGen, MassDNS and HTTPX-based live-host detection. It is also the recon engine behind AttackGrid.

![Bash](https://img.shields.io/badge/Bash-0d1117?style=flat-square&logo=gnubash&logoColor=00ff41)
![Amass](https://img.shields.io/badge/Amass-0d1117?style=flat-square&logoColor=00ff41)
![Subfinder](https://img.shields.io/badge/Subfinder-0d1117?style=flat-square&logoColor=00ff41)
![Assetfinder](https://img.shields.io/badge/Assetfinder-0d1117?style=flat-square&logoColor=00ff41)
![Findomain](https://img.shields.io/badge/Findomain-0d1117?style=flat-square&logoColor=00ff41)
![MassDNS](https://img.shields.io/badge/MassDNS-0d1117?style=flat-square&logoColor=00ff41)

### Hands-On Pentesting Lab

An isolated multi-machine lab (Kali Linux, Metasploitable2, Windows 7) for simulating enterprise attack scenarios: port and service enumeration, CVE research, targeted Metasploit exploitation, privilege escalation, persistence, and full attack chains written up with remediation recommendations.

---

## `~/toolkit`

<div align="center">

| | |
|---|---|
| **Web & API** | `OWASP Top 10` `SQLi` `XSS` `CSRF` `IDOR` `SSRF` `Auth Testing` |
| **Tools** | `Burp Suite` `Metasploit` `Nmap` `Wireshark` `Nessus` `Nikto` `Nuclei` |
| **Recon** | `Attack Surface Discovery` `OSINT` `Network Recon` `Risk Assessment` |
| **SIEM & Detection** | `Splunk` `Wazuh` `Sysmon` `Windows Event Logs` `Linux Logs` |

![Python](https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff41)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=for-the-badge&logo=gnubash&logoColor=00ff41)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=00ff41)
![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=00ff41)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=00ff41)
![Kali](https://img.shields.io/badge/Kali_Linux-0d1117?style=for-the-badge&logo=kalilinux&logoColor=00ff41)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-0d1117?style=for-the-badge&logo=burpsuite&logoColor=00ff41)
![Splunk](https://img.shields.io/badge/Splunk-0d1117?style=for-the-badge&logo=splunk&logoColor=00ff41)

</div>

---

## `~/achievements`

```text
[+] Top 3% globally on TryHackMe
[+] 100+ HackTheBox & TryHackMe machines completed
[+] 100+ security assessments on web applications
[+] 10+ valid vulnerabilities reported (IDOR, XSS, auth bypass)
[+] 8+ technical walkthroughs published on Medium
```

<div align="center">

[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Umang.Mishra?utm_campaign=social_share&utm_medium=social&utm_content=profile&cardVersion=45c818b9374d&utm_source=copy&share_date=2026-11-12&sharerId=67bb0ad8fa3e551288d88129)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://profile.hackthebox.com/profile/019e1bca-30a3-71e4-a7ba-4c809ae8ba64?utm_medium=copy_url)
[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/YOUR_H1_USERNAME)
[![Intigriti](https://img.shields.io/badge/Intigriti-161A36?style=for-the-badge&logoColor=white)](https://app.intigriti.com/profile/YOUR_INTIGRITI_USERNAME)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@YOUR_MEDIUM_USERNAME)

</div>

---

## `~/certifications`

| Certification | Issuer | Year |
|---|---|---|
| Certified LLM Security Professional (CLLMSP) | RedTeam Leaders Academy | 2026 |
| Certified Ransomware Protection Officer (CRPO) | EU Cyber Academy | 2026 |
| Certified Cybersecurity Educator Professional (CCEP) | RedTeam Leaders Academy | 2026 |
| Android Bug Bounty Hunting: Hunt Like a Rat | EC-Council | 2025 |
| Red Hat System Administration I | Red Hat | 2025 |

---

## `~/github-stats`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=umang-mishra23&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=umang-mishra23&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=umang-mishra23&background=0d1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e&stroke=30363d&hide_border=true" />

</div>

---

## `~/contact`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00ff41)](https://linkedin.com/in/-umangmishra)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00ff41)](mailto:umangmishra2327@gmail.com)

```text
[ Open to internships, VAPT collaborations and responsible-disclosure work. ]
[ All testing is done ethically, with permission, in legal environments.    ]
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,100:000000&height=100&section=footer" width="100%" />

</div>
