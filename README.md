<div align="center">

<img src="https://raw.githubusercontent.com/Elouzi-art/assets/main/cinematic-red.svg" alt="Salmane Elouzi" width="100%"/>

<p>
  <a href="#featured-project">Featured</a> &nbsp;|&nbsp;
  <a href="#legit-lab">Legit-Lab</a> &nbsp;|&nbsp;
  <a href="#projects">Projects</a> &nbsp;|&nbsp;
  <a href="#training">Training</a> &nbsp;|&nbsp;
  <a href="#lab">Lab</a> &nbsp;|&nbsp;
  <a href="#get-in-touch">Contact</a>
</p>

</div>

---

## About

```python
class SalmaneElouzi:
    role      = "Information security engineer"
    school    = "UCA"
    focus     = ["Cybersecurity", "Reverse engineering", "Malware analysis", "Networking", "Embedded"]
    languages = ["C", "C++", "Bash", "Python", "PowerShell"]
    lab       = ["FLARE VM", "TryHackMe", "Crackmes"]
    devops    = ["GitLab CI/CD", "Agile", "Docker"]
    mission   = "Build tools and learning projects that make security easier to learn"
```

- Currently building **CyberAI Command Center**
- Published **Legit-Lab**, a URL and PDF analysis tool available on Docker Hub
- Learning malware analysis, reverse engineering, embedded security and space red teaming
- Practicing Agile methods and CI/CD pipelines on GitLab
- Open to open-source collaboration, tutoring and academic contributions

---

## Featured project

### [CyberAI Command Center](https://github.com/Elouzi-art/cyberai-command-center)

![Status](https://img.shields.io/badge/Status-In%20development-ff2e2e?style=flat-square&labelColor=0a0a0a)

My largest project so far: a command center that brings AI and security tooling together in one place. It is under active development, and feedback is welcome.

---

## Legit-Lab

### [Fast URL and PDF security analysis](https://github.com/Elouzi-art/legit-lab)

[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-elouzi09%2Flegit--lab-ff2e2e?style=flat-square&logo=docker&logoColor=white&labelColor=0a0a0a)](https://hub.docker.com/r/elouzi09/legit-lab)
![Pulls](https://img.shields.io/docker/pulls/elouzi09/legit-lab?style=flat-square&color=ff2e2e&labelColor=0a0a0a)
![Size](https://img.shields.io/docker/image-size/elouzi09/legit-lab/latest?style=flat-square&color=ff2e2e&labelColor=0a0a0a)

An open-source triage tool that analyzes suspicious URLs and PDF documents through several independent detection layers.

| Layer | What it does |
|---|---|
| Static heuristics | Typosquatting, raw IPs, unusual TLDs, homographs, embedded JavaScript and automatic actions in PDFs |
| Threat intelligence | VirusTotal, URLhaus and Google Safe Browsing (optional) |
| Machine learning | Experimental phishing risk score for URLs, using logistic regression |
| AI summaries | Gemini or DeepSeek, with a template-based report when no key is set |
| Languages | English, French, Arabic |

```bash
docker pull elouzi09/legit-lab:latest
docker run --rm -p 5000:5000 elouzi09/legit-lab:latest
```

Then open [http://localhost:5000](http://localhost:5000). No API key is needed for the base analysis.

---

## Projects

| Project | Description | Stack |
|---|---|---|
| [**Legit-Lab**](https://github.com/Elouzi-art/legit-lab) | URL and PDF security analysis tool, published on [Docker Hub](https://hub.docker.com/r/elouzi09/legit-lab) | Python, Flask, Docker |
| [**Cyberboard**](https://github.com/Elouzi-art/Cyberboard) | Personal mission control for security students | Laravel, MySQL |
| [**OnePlus-7T-HD1903-public**](https://github.com/Elouzi-art/OnePlus-7T-HD1903-public) | Complete Magisk and NetHunter guide | Android, NetHunter |
| [**The-Ride-2D**](https://github.com/Elouzi-art/The-Ride-2D) | 2D game in C++ with SDL2 | C++, SDL2 |

### Open-source contributions

| Project | What I'm doing | Stack |
|---|---|---|
| [**FlatSat**](https://github.com/Elouzi-art/FlatSat) | Working on my fork of a hardware and firmware learning platform for space red teaming, with the goal of contributing firmware patches back to the project | C, Embedded |

---

## Training

| Training | Status |
|---|---|
| TryHackMe: offensive and defensive paths | **In progress** |
| FLARE VM: malware analysis lab | **Ongoing practice** |
| GitLab: Agile and CI/CD pipelines | **Learning** |

<a href="https://tryhackme.com/p/SOLIDux"><img src="https://tryhackme-badges.s3.amazonaws.com/SOLIDux.png" alt="TryHackMe" height="120"/></a>

---

## Lab

### Crackmes and reverse engineering

- Solving crackme challenges: static and dynamic analysis, patching, keygens
- Tools: `Ghidra` · `x64dbg` · `IDA Free` · `GDB` · `Radare2`

### Malware analysis with FLARE VM

- Isolated lab built on **FLARE VM**
- Static analysis: `PEStudio` · `Detect It Easy` · `CFF Explorer` · `FLOSS`
- Dynamic analysis: `Procmon` · `Process Hacker` · `Wireshark` · `FakeNet-NG`
- Reverse engineering: `Ghidra` · `x64dbg` · `dnSpy`

> All analysis runs in an isolated environment with snapshots and a host-only network.

### GitLab, Agile and CI/CD

Profile: [gitlab.com/s.elouzi0010](https://gitlab.com/s.elouzi0010)

- CI/CD pipelines with `.gitlab-ci.yml`: build, test, security scan, deploy
- Agile workflow: sprints, backlog, issues, boards, merge requests
- DevSecOps basics: SAST and dependency scanning

---

## Stack

<img src="https://skillicons.dev/icons?i=c,cpp,py,bash,powershell,php,laravel,flask,mysql,linux,kali,git,gitlab,docker&theme=dark" alt="Stack"/>

**Areas:** `Malware Analysis` · `Reverse Engineering` · `Network Security` · `Embedded Security` · `CTF` · `Red Teaming` · `DevSecOps`

---

## GitHub stats

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Elouzi-art&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=ff2e2e&icon_color=ff2e2e&text_color=c9d1d9" alt="GitHub stats"/>

---

## Looking for

- Open-source work in embedded security, AI for cybersecurity and educational tooling
- CTFs and training platforms to contribute to
- Feedback and contributors for **CyberAI Command Center** and **Legit-Lab**
- Ways to share what I learn through guides, write-ups and tutoring

---

## Get in touch

[Email](mailto:4un78kmp9@mozmail.com) &nbsp;|&nbsp;
[GitHub](https://github.com/Elouzi-art) &nbsp;|&nbsp;
[GitLab](https://gitlab.com/s.elouzi0010) &nbsp;|&nbsp;
[Docker Hub](https://hub.docker.com/r/elouzi09/legit-lab) &nbsp;|&nbsp;
[TryHackMe](https://tryhackme.com/p/SOLIDux)
