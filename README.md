# 🛡️ Mission SecureNet — Cybersecurity Awareness Game for Students

> **A free, browser-based, interactive cybersecurity education game for school students aged 10–16.**
> No downloads. No login required. Works on any school computer, Chromebook, or tablet.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made for Schools](https://img.shields.io/badge/Made%20For-Schools%20%26%20Students-blue.svg)]()
[![No Install Needed](https://img.shields.io/badge/No%20Install-Just%20Open%20in%20Browser-orange.svg)]()
[![Age Group](https://img.shields.io/badge/Age%20Group-10–16%20Years-purple.svg)]()
[![Levels](https://img.shields.io/badge/Missions-9%20Levels%20%2B%20Final%20Boss-red.svg)]()

---

## 🌐 Play Now

> **[▶ Click here to open the game](./mission-securenet-v2.html)** — just download and open in any browser.
> Teachers: see the [Teacher Dashboard](#-teacher-dashboard--classroom-mode) section below.

---

## 📖 What Is Mission SecureNet?

**Mission SecureNet** is a free, open-source cybersecurity awareness game designed to teach school students about online safety in an engaging, story-driven format. Instead of boring slideshows or quizzes, students become **Cyber Agents** defending the fictional **CyberCity** from hackers, scammers, and online threats.

The philosophy: **Fun first. Learning second.** Every game mechanic is designed to create a memorable experience that sticks — because students remember what they *do*, not just what they *read*.

This project is built for:
- 🏫 **Schools** running cyber safety or digital literacy programs
- 👩‍🏫 **Teachers** who want interactive classroom tools without technical setup
- 🧒 **Students (ages 10–16)** learning about internet safety
- 👨‍👩‍👧 **Parents** wanting to teach kids about online safety at home
- 💻 **Hackathons** and EdTech competitions focused on digital literacy

---

## 🎮 Game Features

### ✅ 9 Playable Missions + Final Boss
| Level | Mission | Cyber Threat Covered |
|-------|---------|----------------------|
| 🔐 01 | The Password Vault | Password strength, 2FA |
| 🎣 02 | The Phishing Trap | Phishing emails, fake domains |
| 👥 03 | Social Media Danger | Stranger danger, privacy settings |
| 📱 04 | The OTP Scam | Bank fraud calls, OTP safety |
| 💬 05 | Cyberbullying Rescue | Cyberbullying, reporting, support |
| 🎭 06 | The Deepfake Lab | AI-generated fake videos, misinformation |
| 🦠 07 | Malware Maze | Malicious downloads, fake pop-ups |
| 👣 08 | Digital Footprint | Online privacy, permanent data traces |
| 💀 09 | MASTER HACKER | Final Boss — rapid-fire quiz on all topics |

### 🤖 BYTE — Your AI Mascot Guide
A custom SVG robot companion who gives **level-specific cyber tips** at the start of every mission. Students can click BYTE anytime for a hint. Designed to make the game feel like a guided adventure, not a test.

### 🔊 Sound Effects Engine
Built entirely with the **Web Audio API** — zero external files, zero loading time. Includes:
- ✅ Correct answer chimes
- ❌ Wrong answer buzz
- ⚡ XP reward sounds
- 🏆 Level complete fanfare
- 🔔 Boss battle alerts

Fully toggleable with a single click for quiet classroom environments.

### 🏆 XP System + Achievement Badges
- Students earn **XP points** for completing each level
- Bonus **achievement badges** unlock for flawless runs, speed, and streaks
- A **printable Cyber Hero Certificate** is awarded on completion — great for school bulletin boards and parent evenings

### 👩‍🏫 Teacher Dashboard + Classroom Mode
- Password-protected teacher portal (no server required — runs locally)
- **Class code system** — share a code with students to track their progress
- **Student progress table** — see each student's XP, completed missions, and mistake count
- **Weak Areas analysis** — identifies which cyber threats the class struggles with most, with teaching recommendations
- **Alerts** — flags students who may need additional support
- **CSV export** and **print report** for school records

---

## 🖥️ How to Use

### For Students
1. Download `mission-securenet-v2.html`
2. Open it in any web browser (Chrome, Firefox, Edge, Safari)
3. Enter your agent codename and start playing
4. Complete all 9 missions to earn your Cyber Hero Certificate

### For Teachers
1. Download `mission-securenet-v2.html`
2. Open it in a browser and click **"TEACHER PORTAL"** on the title screen
3. Log in with password: `teacher123` *(change this in the source code before deploying)*
4. Share the class code shown on your dashboard with students
5. Monitor student progress in real time via the dashboard tabs

### For Schools / IT Administrators
- The entire game is a **single `.html` file** — no server, no database, no internet connection required after download
- Can be placed on a school shared drive, VLE/LMS, Google Classroom, or any intranet
- Works on Windows, macOS, Linux, Chromebooks, iPads, and Android tablets
- Tested on Chrome 90+, Firefox 88+, Edge 90+, Safari 14+

---

## 📚 Curriculum Alignment

Mission SecureNet covers topics aligned with digital literacy and e-safety frameworks including:

- **UK:** PSHE e-safety objectives, Computing curriculum (KS3), Ofsted online safety guidance
- **India:** CBSE IT literacy, Cyber Safety guidelines by Ministry of Education
- **US:** CISA K-12 cybersecurity education framework, Common Sense Media digital citizenship curriculum
- **Global:** UNESCO ICT Competency Framework, ISTE Standards for Students

**Topics covered in depth:**
- Password safety and two-factor authentication (2FA)
- Identifying phishing emails and social engineering
- Social media privacy and stranger danger
- OTP fraud and telephone scams
- Cyberbullying — recognising, reporting, and supporting victims
- Deepfakes and AI-generated misinformation
- Malware, malicious downloads, and fake pop-ups
- Digital footprints and long-term online reputation

---

## 🧠 Pedagogical Approach

Mission SecureNet uses **scenario-based learning** — a research-backed approach where students make decisions in realistic situations rather than passively consuming information.

Key design principles:
- **Active recall** — students make choices, not just read answers
- **Immediate feedback** — every wrong answer triggers an explanation, not just a red X
- **Emotional anchoring** — story-driven scenarios (a bullied friend, a phone scammer, a viral deepfake) create emotional memory hooks
- **Spaced repetition** — the Final Boss revisits all topics from earlier levels
- **Intrinsic motivation** — XP, badges, and a printable certificate create genuine progression feel

---

## 🔧 Technical Details

| Property | Value |
|----------|-------|
| **Technology** | Vanilla HTML5, CSS3, JavaScript (ES6+) |
| **Dependencies** | Google Fonts (Orbitron, Exo 2) — loaded from CDN |
| **File size** | ~95 KB (single file, no assets) |
| **Audio** | Web Audio API (no external files) |
| **Storage** | No cookies, no localStorage, no tracking |
| **Internet required** | Only for Google Fonts (game works offline if fonts cached) |
| **Offline PWA** | Planned for v3.0 |

### Privacy & Safety
- **Zero data collection.** No analytics, no tracking pixels, no cookies.
- No student data leaves the device.
- No login or account creation required for students.
- GDPR, COPPA, and FERPA friendly by design.
- Fully self-contained — safe to use on school networks.

---

## 🗺️ Roadmap

### v2.0 (Current)
- [x] 9 missions including Deepfakes, Malware, Digital Footprint
- [x] BYTE mascot with level-specific tips
- [x] Web Audio sound engine
- [x] Teacher Dashboard with class codes and progress tracking
- [x] XP system and achievement badges
- [x] Printable Cyber Hero Certificate

### v3.0 (Planned)
- [ ] Offline PWA — install on tablets, works without internet
- [ ] Multiplayer classroom mode — head-to-head cyber challenge
- [ ] Multi-language support (Hindi, Spanish, French, Arabic)
- [ ] Difficulty levels (Easy / Medium / Hard)
- [ ] Lives system — 3 chances per mission
- [ ] Backend integration (Node.js + SQLite) for persistent class rosters
- [ ] School SSO login (Google Workspace, Microsoft 365)
- [ ] Additional levels: Fake News, Dark Web awareness, Safe Passwords II
- [ ] Animated cutscenes between levels (comic-book style)

---

## 🤝 Contributing

Contributions are welcome — especially from:
- **Teachers** who want to suggest new scenarios or improve existing ones
- **Students** who find bugs or have ideas for new game mechanics
- **Developers** who want to help build v3.0 features
- **Translators** who can help localise the game for non-English schools

### How to Contribute
1. Fork this repository
2. Create a feature branch: `git checkout -b feature/new-level-fakeshopping`
3. Make your changes to `mission-securenet-v2.html`
4. Test in Chrome, Firefox, and on a mobile device
5. Submit a Pull Request with a clear description of what you added

### Reporting Issues
Please open a GitHub Issue for:
- Bugs or browser compatibility problems
- Factually incorrect cybersecurity advice in the game
- Accessibility concerns
- Suggestions for new levels or scenarios

---

## 👨‍🏫 Used This in Your Classroom?

We'd love to hear about it! Open a [Discussion](../../discussions) or tag us. We're collecting:
- Student feedback and engagement stories
- Teacher tips for getting the most out of the game
- School screenshots for the project gallery

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute for educational purposes.

```
MIT License — Copyright (c) 2025 Mission SecureNet

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, and distribute it, subject to
the condition that the above copyright notice appears in all copies.
```

---

## 🙏 Acknowledgements

- Inspired by real cybersecurity threats affecting school students in India and globally
- Sound design using the Web Audio API — no external libraries
- Typography: [Orbitron](https://fonts.google.com/specimen/Orbitron) and [Exo 2](https://fonts.google.com/specimen/Exo+2) via Google Fonts
- Built as a hackathon project with a mission to make cyber safety education accessible to every school, everywhere

---

## 📬 Contact & Links

- 🐛 **Report a bug:** [Open an Issue](../../issues)
- 💡 **Request a feature:** [Start a Discussion](../../discussions)
- 🏫 **School enquiries:** Open an issue tagged `school-deployment`
- 🌐 **Live demo:** *(Add your GitHub Pages or Netlify link here)*

---

<div align="center">

**Built with ❤️ for every student who deserves to be safe online.**

*CyberCity is counting on you, Agent.*

🛡️ **[Play Mission SecureNet Now](./mission-securenet-v2.html)** 🛡️

</div>

---

### 🔍 Keywords
*cybersecurity game for students · cyber awareness game for kids · internet safety game school · phishing game for teenagers · online safety interactive game · cyberbullying education game · digital literacy game · cyber security classroom activity · free cybersecurity education tool · cyber hero game · internet safety lesson plan · cybersecurity quiz for students · deepfake awareness game · malware education game · password safety game · digital footprint lesson · OTP fraud awareness · cyber safety India schools · CBSE cyber safety · KS3 computing game · e-safety classroom tool*
