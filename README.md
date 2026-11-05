<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:58a6ff&height=200&section=header&text=Matt%20Petosa&fontColor=ffffff&fontSize=58&fontAlignY=36&desc=AI%20Apps%20%E2%80%A2%20Software%20%E2%80%A2%20Websites%20%E2%80%A2%20Automation%20%E2%80%A2%20DevOps&descAlignY=56&descSize=18" width="100%" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=AI+App+Developer;Software+Developer;Website+Developer;Automation+Engineer;DevOps+Engineer;Systems+Engineer;Cloud+Engineer;Network+Engineer&font=Fira%20Code&size=22&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=460&height=45)](https://github.com/mattpetosa)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square)](https://www.linkedin.com/in/matthew-petosa-21b86265/)
[![MHP Technology](https://img.shields.io/badge/MHP%20Technology-1f6feb?style=flat-square&logo=googlechrome&logoColor=white)](https://mhptechnology.com)
![Profile views](https://komarev.com/ghpvc/?username=mattpetosa&label=Profile%20views&color=1f6feb&style=flat-square)

</div>

---

## 💫 About Me

I'm an **AI app, software and website developer** and an **automation and DevOps engineer**. I design and ship production software end to end: Windows desktop apps, web apps, and the servers, pipelines and infrastructure they run on. AI runs through all of it, both as features inside the products (chat assistants that use tools, vision-based moderation) and as agents in my own workflow for planning, building, testing and reviewing code.

By day I deploy and automate **Waters Empower 3** lab software, which is where Empower Smart Tools came from. I also run **MHP Technology LLC** for client work and side projects, hosted on servers I build and run myself: Debian, nginx, Docker and Cloudflare, with automated deploys.

- 🔭 **Currently building:** Empower Smart Tools and the VIP & Suites storefront
- ⚙️ **Automation & DevOps:** release pipelines, self-updating apps, scripted installs, CI, backups and monitoring across a fleet of self-hosted services
- 🤖 **AI:** apps on the Claude API (tool use, vision, evals) and agent-driven development with Claude Code
- 🧰 **Comfort zone:** Python, C# / .NET, JavaScript / TypeScript, Flask, nginx, Docker, and a terminal
- 🏎️ **Off-keyboard:** cars, motorcycles, and anything with an engine

## 🧪 Empower Smart Tools

A suite of tools for **Waters Empower 3** that turns long manual checklists into repeatable, verified jobs. Nine tools, one site: [empower.mhpwebserver.com](https://empower.mhpwebserver.com)

The Windows apps share one core: signed self-updates, license keys, and release builds that are obfuscated and smoke-tested before they reach a download channel.

### 🖥️ Windows apps

| Tool | What it does | Status |
| :--- | :--- | :--- |
| **[Smart Deploy](https://github.com/mattpetosa/empower-smart-deploy-releases)** | Automated Empower 3 installs. Runs the prep scripts and pre-flight checks, then drives the installer for a consistent, audit-ready setup in minutes. Includes an offline ISO builder. | ✅ Released |
| **[Smart Recovery](https://github.com/mattpetosa/empower-smart-recovery-releases)** | Rebuilds a corrupted Empower database and tests disaster-recovery scripts, so you know the DR plan restores cleanly before you need it. | ✅ Released |
| **[Smart License Audit](https://github.com/mattpetosa/empower-smart-license-audit-releases)** | Checks a customer's licenses and users across all their instances. The app collects read-only and uploads sealed; the [audit site](https://audit.mhpwebserver.com) produces a plain-language report. | ✅ Released |
| **[Smart Project Migration](https://github.com/mattpetosa/empower-smart-project-migration-releases)** | Backs up, restores and moves Empower projects between databases, verifying every hop with checksums, raw-data compares and before/after contents. | ✅ Released |
| **[Smart Project Backup](https://github.com/mattpetosa/empower-smart-project-backup-releases)** | Scheduled, verified per-project backups, so one project can be put back without rolling the whole database back. Email alerts through your own SMTP server. | 🧪 Pre-release |
| **Smart Object Export** | Moves users, groups, permissions, policies and other system objects from an old database to a new one through an encrypted export file. | 🚧 In development |

### 🌐 Web tools

| Tool | What it does | Status |
| :--- | :--- | :--- |
| **[Smart License Cleaner](https://github.com/mattpetosa/empower-smart-license-cleaner)** | Turns a Licensing Wizard PDF or Checksum report into a clean Excel sheet and portal CSV, in the browser. Offline single-file version too. | ✅ Released |
| **[Smart IQ Filler](https://github.com/mattpetosa/empower-smart-iq-filler)** | Fills in the Servers IQ PDF from the server's own system files and shows where every value came from. | ✅ Released |
| **[Smart License Extension](https://github.com/mattpetosa/empower-smart-license-extension)** | Chrome extension that turns an order's license assets into a License Cleaner CSV or XLSX in one click. | ✅ Released |

Bugs and feature requests for the whole suite: [smart-tools-feedback](https://github.com/mattpetosa/smart-tools-feedback)

## 🛠️ Side Projects

| Project | What it is |
| :--- | :--- |
| **🤖 VIP & Suites** | Storefront for **luxury suites, clubs and VIP seats** with one flat all-in price and interactive venue maps. Includes an AI chat assistant built on Claude that searches live events and hands off to a human concierge. Being rebuilt from the ground up. |
| **🤖 [The Public Homepage](https://thepublichomepage.com)** | Pay to put your own photo on the page, so the public decides what's on it. Every upload passes AI vision moderation, and anything untrusted runs in Docker isolation. |
| **[BlueChipGarage](https://bluechipgarage.com)** | Live auction and classified listings for sports cars and exotics, with market value from real completed sales and a full cost-of-ownership projection. |
| **[Mission Control](https://mission.mhpwebserver.com)** | Space launch and active-mission dashboard with a baked SVG world map, live day/night terminator and rate-limit-aware caching. [Source](https://github.com/mattpetosa/mission-dashboard) |
| **[Event Weather Tracker](https://github.com/mattpetosa/event-weather-tracker)** | Self-hostable weather comparison for an event's exact hours across NWS, MET Norway and the major forecast models, with a verdict. |
| **[White Label Gym Platform](https://palker.mhpwebserver.com)** | A gym site any training gym can run under its own brand: class booking and checkout, member portal, trainer back office and a late-cancellation fee ladder. |
| **Browser Games** | three.js and TypeScript games with real-time online multiplayer: party lobbies, up to 16 players, server-authoritative netcode. |

## 💻 Tech Stack

**Languages**<br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge)
![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=for-the-badge&logo=gnubash&logoColor=white)

**AI**<br>
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-191919?style=for-the-badge&logo=anthropic&logoColor=white)

**Web & Backend**<br>
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Gunicorn](https://img.shields.io/badge/gunicorn-%23298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Three.js](https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white)
![esbuild](https://img.shields.io/badge/esbuild-%23FFCF00.svg?style=for-the-badge&logo=esbuild&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-5469d4?style=for-the-badge&logo=stripe&logoColor=white)
![Chrome Extensions](https://img.shields.io/badge/Chrome%20Extensions-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)

**Desktop & Data**<br>
![.NET](https://img.shields.io/badge/.NET%208%20%2F%20WPF-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge)

**Infrastructure & Testing**<br>
![NGINX](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=for-the-badge&logo=pytest&logoColor=2f9fe3)

## 📊 GitHub Stats

<div align="center">

![Streak](https://streak-stats.demolab.com/?user=mattpetosa&theme=github-dark-blue&hide_border=true&border_radius=8)

<!--
github-readme-stats.vercel.app (stats + top-langs cards), github-profile-trophy and
github-readme-activity-graph.vercel.app were down / payment-disabled (402) as of 2026-11-04. Re-add here if they return:
![](https://github-readme-stats.vercel.app/api?username=mattpetosa&theme=dark&include_all_commits=true&count_private=true)
-->

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,50:1f6feb,100:0d1117&height=120&section=footer" width="100%" />
