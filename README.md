[README.md](https://github.com/user-attachments/files/26307982/README.md)
# 🛡️ DMRC CyberQuest — साइबर सुरक्षा जागरूकता पोर्टल

> **An interactive cybersecurity awareness platform built specifically for Delhi Metro Rail Corporation (DMRC) — based on real vendor ecosystem and actual vulnerabilities.**

🌐 **Live Demo:** `https://[your-username].github.io/dmrc-cyberquest/`

---

## 🚇 What is DMRC CyberQuest?

DMRC CyberQuest is a gamified cybersecurity awareness portal inspired by [mr-r3b00t/cyberquest](https://mr-r3b00t.github.io/cyberquest/). It presents **8 real-world cyber attack scenarios** tailored to DMRC's actual technology stack, vendors, and infrastructure — helping employees recognise and respond to threats they may actually encounter.

The portal is fully **bilingual (Hindi 🇮🇳 + English)** and requires **no installation, no server, no dependencies** — just open `index.html` in any browser.

---

## 🎯 Features

- 🎮 **8 Interactive Scenarios** — scenario-based quiz format with multiple choice answers
- 🌐 **Bilingual** — full Hindi and English toggle, switch anytime
- ⭐ **Score Tracking** — 100 points per scenario, 800 total
- 🏅 **Achievement Badges** — one badge unlocked per completed scenario
- 📊 **Progress Bar** — visual completion tracker
- 🏆 **Completion Certificate** — awarded on finishing all 8 scenarios
- 📱 **Responsive Design** — works on desktop and mobile
- ✅ **Zero Dependencies** — pure HTML + CSS + JavaScript, no npm, no build step

---

## 🔍 Scenarios & Vendor Coverage (OSINT-Based)

All scenarios are grounded in **real DMRC vendors and publicly documented vulnerabilities**:

| # | Scenario | Vendor | Threat Type | Difficulty |
|---|----------|--------|-------------|------------|
| 1 | The Thales Phishing Trap | **Thales Group** (AFC & Ticketing) | Phishing / BEC | 🟢 Easy |
| 2 | Smart Card Exploit | **NXP MiFare DESFire EV1 + Thales** | Hardware Vulnerability | 🟡 Medium |
| 3 | SCADA Signaling Attack | **Siemens / Alstom** (OT/Train Control) | ICS / OT Attack | 🔴 Hard |
| 4 | Fake SAP Vendor Call | **SAP ERP** (Finance & Procurement) | Vishing | 🟢 Easy |
| 5 | Station PC Ransomware | **DMRC Ticketing Terminals** | USB Drop / Ransomware | 🟡 Medium |
| 6 | CCTV Network Hijack | **14,600+ CCTV Network** | Data Exfiltration | 🔴 Hard |
| 7 | XSS Web Injection | **DMRC Intranet** (Real May 2024 CVE) | Stored XSS | 🟡 Medium |
| 8 | Vendor Portal Insider Threat | **vpp.dmrc.org** (VPP) | Insider Threat / DLP | 🔴 Hard |

### 📌 Real-World Basis
- **Scenario 2** is based on a vulnerability discovered by researcher Nikhil Kumar Singh in 2022 — NXP MiFare DESFire EV1 cards allowed free top-ups due to missing payment validation.
- **Scenario 7** is based on a Stored XSS reported in DMRC's intranet in May 2024 by researcher Abhishek Aswal.
- **Scenario 3** references the DMRC UITP Urban Rail Conference 2025 theme of IT-OT convergence security.
- All vendor references are based on public OSINT and DMRC's known technology partnerships.

---

## 🚀 How to Use

### Option 1 — GitHub Pages (Recommended)
1. Fork or clone this repository
2. Go to **Settings → Pages → Branch: main → Save**
3. Access at `https://[username].github.io/dmrc-cyberquest/`

### Option 2 — Run Locally
```bash
git clone https://github.com/[username]/dmrc-cyberquest.git
cd dmrc-cyberquest
# Just open index.html in any browser — no server needed!
```

### Option 3 — Direct Download
Download `index.html` and open it in any browser.

---

## 🏗️ Tech Stack

```
Pure HTML5 + CSS3 + Vanilla JavaScript
No frameworks • No npm • No build tools • No backend
Single file: index.html (~800 lines)
```

---

## 📚 Learning Objectives

After completing all scenarios, participants will be able to:

- ✅ Identify phishing and vishing attacks from vendor impersonation
- ✅ Understand OT/ICS cyber risks in metro rail signaling systems
- ✅ Recognise USB drop and ransomware response procedures
- ✅ Apply responsible disclosure principles for hardware vulnerabilities
- ✅ Understand Stored XSS impact in internal web applications
- ✅ Implement insider threat detection and response steps
- ✅ Follow CERT-In reporting obligations for critical infrastructure incidents

---

## ⚠️ Disclaimer

> This portal is built for **educational and cybersecurity awareness purposes only**.
> All vendor names (Thales, NXP, Siemens, Alstom, SAP) are referenced for educational context based on public information.
> Vulnerability scenarios are based on publicly disclosed findings and do not represent current system states.
> This project is not officially affiliated with DMRC.

---

## 🙏 Inspired By

- [mr-r3b00t/cyberquest](https://mr-r3b00t.github.io/cyberquest/) — the original CyberQuest project
- DMRC Cyber Security Awareness Month initiatives
- UITP India Urban Rail Conference 2025 — Cybersecurity in Metro Systems

---

## 📄 License

MIT License — Free to use, adapt, and share for awareness purposes.

---

<div align="center">
  <b>🚇 Delhi Metro Rail Corporation | Cyber Security Awareness</b><br>
  <i>दिल्ली मेट्रो रेल कॉर्पोरेशन | साइबर सुरक्षा जागरूकता</i>
</div>
