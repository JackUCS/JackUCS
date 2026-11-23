<div align="center">

<img src="assets/banner.svg" alt="Jack Jeffery — full-stack developer" width="100%" />

building systems end to end. the database schema, the API, the frontend, and the deploy.
Recent work spans web platforms, Discord automation, and a self-contained
defensive-security cyber range.

</div>

---

## 🛠 Tech I work with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frameworks & libraries**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Infrastructure & security**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Vagrant](https://img.shields.io/badge/Vagrant-1868F2?style=for-the-badge&logo=vagrant&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-00A98F?style=for-the-badge&logo=suricata&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🏆 Featured project

### Blue Team Target VM — Cyber Range
> 🔒 Private repository — happy to walk through it on request

A pre-built, portable **Ubuntu 22.04 LTS defensive-analysis desktop** shipped as a
single OVA. Designed to be handed to a student on a USB stick and used with
**no internet, no Vagrant, and no setup steps** boot it, log in, investigate.

It bundles Suricata, Zeek and Wireshark alongside a custom interactive incident
console and a CTFd scoreboard, then runs **six self-starting graded scenarios**
that plant realistic but entirely benign attacks:

| # | Scenario | Category | Points |
|---|----------|----------|--------|
| 1 | C2 Beacon Detection | Network Forensics | 200 |
| 2 | DNS Tunnelling Detection | Network Forensics | 250 |
| 3 | File Integrity Violation | Host Forensics | 200 |
| 4 | Web Server Compromise | Host Forensics | 300 |
| 5 | Lateral Movement / Pivot | Network Forensics | 300 |
| 6 | Insider Data Exfiltration | Incident Response | 250 |

Each scenario releases a **CTFd-compatible flag only when the objective is
genuinely met** — typically "identify *and* contain", not just spot it.

**Engineered for real deployment:** a shared shell library drives flag state across
all scenarios, a Python API exposes progress, a React/TypeScript HUD serves the
story and reference material, and CTFd is seeded and bootstrapped automatically.
Full instructor guide, investigation handbook, glossary and troubleshooting docs ship
with it.

`Python` · `TypeScript` · `React` · `Bash` · `Vagrant` · `Proxmox` · `Suricata` · `Zeek` · `CTFd`

---

## 📌 Other projects

### linkd — live at [lnkd.lol](https://lnkd.lol)
> 🔒 Private repository — running in production

A self-hosted link-in-bio profile builder: 16 themes, 4 layouts, 12 custom cursors,
11 animated username effects, 7 canvas particle effects, background audio with an
upload library, a media host and real analytics — every profile on its own URL.

Express 5 with PostgreSQL on **Supabase**, JWT + bcrypt auth, and direct-to-**Cloudflare R2**
uploads via presigned URLs — the 25 MB file never touches the server, and storage stays
cheap and durable when the app's own filesystem is ephemeral. A Playwright suite covers
the build end to end, including a real-browser upload test against R2.

[**lnkd.lol →**](https://lnkd.lol)

`JavaScript` · `Express` · `PostgreSQL` · `Supabase` · `Cloudflare R2` · `JWT` · `Playwright`

### LocalLink — service-booking marketplace
> 🔒 Private repository — design workup is [public here](https://github.com/JackUCS/LocalLink)

A local-services booking platform built from the design workup up: home, search,
service detail, customer and provider dashboards, and an admin panel. Twelve
purpose-built JS modules behind a shared store, a full theming layer, and a
Playwright layout/regression harness guarding the shared navbar and form styling.

`JavaScript` · `CSS` · `Playwright` · `UX`

### [dhgVAULT](https://github.com/JackUCS/dhgVAULT) — affiliate storefront platform
Express 5 backend with an authenticated admin panel, wishlist system, sharp-based
image pipeline, and an esbuild build step minifying every asset. Includes security
headers, request-IP tracking, and SEO files.

`JavaScript` · `Express` · `Node` · `sharp` · `esbuild`

### [Digital-CV](https://github.com/JackUCS/Digital-CV) — interactive CV & coursework journal
Not a PDF — a live site with light/dark theming, a cursor spotlight, animated grid
background, and dedicated modules and reflective-journal sections.
[View the PDF →](https://github.com/JackUCS/Digital-CV/blob/main/JackJefferyCV.pdf)

`HTML` · `CSS` · `JavaScript`

### [Roblox-Monitoring-Final](https://github.com/JackUCS/Roblox-Monitoring-Final) — automated monitor & alerter
Python service polling game servers via `aiohttp`, persisting state to MySQL, and
pushing webhook alerts. Deployed on Railway with environment-based config.

`Python` · `aiohttp` · `MySQL` · `Railway`

### [PublicInterface](https://github.com/JackUCS/PublicInterface) — Discord slash-command bot
Command interface over a MySQL backend — users register webhook endpoints and the bot
routes alerts to them, with slash-command sync on startup.

`Python` · `discord.py` · `MySQL` · `Railway`

### [CampusConnect-HIGH-Res-images](https://github.com/JackUCS/CampusConnect-HIGH-Res-images)
Entity-relationship diagram and high-resolution interface mockups.

`Database design` · `ERD`

---

## 📊 Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=JackUCS&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JackUCS&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />

</div>

---

## 🧭 About me

- 🎓 Studying at **UCS** — programming, networking, cyber security, data science and web
- 🛡️ Most proud of building the **Blue Team cyber range** end to end
- 🔭 Currently building a **local services booking platform**
- 🌱 Learning **backend architecture and secure deployment**
- 💬 Ask me about **Python bots, Express APIs, or MySQL schemas**

## 🎯 Outside of code

- 🎮 **Gaming** — ARPGs and looter shooters (*Path of Exile 2*, *Destiny 2*),
  hero shooters and battle royales (*Fortnite*, *Apex Legends*), plus *Rocket League*,
  *Call of Duty* and *Geometry Dash*
- 🎧 **Music** — EDM and hyperpop
- 🎨 **Design** — UI mockups, wireframes, and interface work

---

<div align="center">

### 📫 Get in touch

[![GitHub](https://img.shields.io/badge/GitHub-JackUCS-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JackUCS)
[![Email](https://img.shields.io/badge/Email-jack300305@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jack300305@gmail.com)

</div>
