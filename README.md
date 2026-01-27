# 🚩 pwnedByJT.github.io

![GitHub deployments](https://img.shields.io/github/deployments/pwnedByJT/pwnedByJT.github.io/github-pages?style=flat-square&label=Deploy&logo=github)
![Jekyll](https://img.shields.io/badge/Built%20With-Jekyll-cc0000?style=flat-square&logo=jekyll&logoColor=white)
![Size](https://img.shields.io/github/repo-size/pwnedByJT/pwnedByJT.github.io?style=flat-square&color=00ff00)

> **Live Site:** [https://pwnedbyjt.github.io](https://pwnedbyjt.github.io)

This repository contains the source code for my personal Offensive Security portfolio. It is designed to mimic a high-end terminal interface or command center, showcasing my transition from System Administration to Penetration Testing.

## ⚡ Features
* **Custom Theme Engine:** Built on top of `jekyll-theme-hacker` with extensive CSS overrides for a "Tokyo Night" / Cyberpunk aesthetic.
* **CRT Simulation:** Custom SCSS implementation of scanlines, text-shadow glow, and blinking cursor animations.
* **Live API Integration:** Dynamic badges that fetch real-time rank/stats from **Hack The Box** and **TryHackMe**.
* **OpSec Compliance:** Public-facing version of my resume with PII sanitized.
* **Visitor Tracking:** Integrated view counter to monitor traffic.

## 🛠️ Tech Stack
* **Core:** [Jekyll](https://jekyllrb.com/) (Static Site Generator)
* **Hosting:** GitHub Pages (Automated CI/CD)
* **Styling:** SCSS / CSS3 with custom variables for easy theming.
* **Fonts:** 'JetBrains Mono' & 'Share Tech Mono' via Google Fonts.

## 🚀 Local Development
To clone and run this portfolio locally:

```bash
# 1. Clone the repo
git clone [https://github.com/pwnedByJT/pwnedByJT.github.io.git](https://github.com/pwnedByJT/pwnedByJT.github.io.git)

# 2. Enter directory
cd pwnedByJT.github.io

# 3. Install dependencies (Requires Ruby & Bundler)
bundle install

# 4. Run local server
bundle exec jekyll serve

```

## 📂 Directory Structure

* `_config.yml` - Main site configuration and theme settings.
* `assets/css/` - Custom SCSS overrides for the CRT/Terminal effects.
* `_layouts/` - HTML templates for page structure.
* `projects.md` - Documentation of Python scripts and Home Lab topology.
* `writeups.md` - CTF walkthroughs and methodology reports.

---

<div align="center">
<i>© 2026 Justin Turner | "Proof of work is better than promises."</i>
</div>