<p align="center">
  <h1 align="center" style="font-family: 'EB Garamond', serif; font-size: 2.8em;">𝓒𝓡𝓔𝓔𝓟𝓨_𝓜𝓓-𝓥𝟐</h1>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=EB+Garamond&weight=900&size=28&duration=4000&pause=1000&width=520&lines=CREEPY_MD+V2+by+CreepyTech;Like+V3+but+with+Buttons;Hosted+at+v2.creepytech.org;Fork+%2B+Star+%2B+Deploy!" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://files.catbox.moe/f6j3fl.jpeg" alt="CREEPY_MD Banner" width="420" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="rainbow" />
</p>

<p align="center">
  <a href="https://github.com/Daniel432-gift?tab=followers"><img src="https://img.shields.io/github/followers/Daniel432-gift?label=Followers&style=for-the-badge&logo=github" alt="Followers" /></a>
  <a href="https://github.com/Daniel432-gift/CREEPY_MD-V2/stargazers"><img src="https://img.shields.io/github/stars/Daniel432-gift/CREEPY_MD-V2?color=blue&style=for-the-badge&logo=starship" alt="Stars" /></a>
  <a href="https://github.com/Daniel432-gift/CREEPY_MD-V2/network/members"><img src="https://img.shields.io/github/forks/Daniel432-gift/CREEPY_MD-V2?color=red&style=for-the-badge&logo=git" alt="Forks" /></a>
  <a href="https://github.com/Daniel432-gift/CREEPY_MD-V2"><img src="https://img.shields.io/github/repo-size/Daniel432-gift/CREEPY_MD-V2?style=for-the-badge&color=orange" alt="Repo Size" /></a>
  <a href="https://github.com/Daniel432-gift/CREEPY_MD-V2/graphs/commit-activity"><img src="https://img.shields.io/badge/Maintained%3F-Yes-yellow?style=for-the-badge" alt="Maintained" /></a>
</p>

---

## 🔥 What is CREEPY_MD-V2?

**CREEPY_MD-V2** is the official second-generation WhatsApp Multi-Device bot from **CreepyTech** (Danny Tech).  
It is intentionally built to feel almost identical to the later **V3** experience, with one very important difference that users constantly asked for:

> **V2 has interactive buttons.**

While V3 moved toward a cleaner text / list-message style in some deployments, V2 keeps the classic and highly requested **button-based reply system**. This means menus, confirmation dialogs, and many command responses appear as actual WhatsApp buttons that users can simply tap instead of typing. For groups and less technical users this is a massive usability upgrade.

In short:
- Same powerful core as the modern CreepyTech bots
- Same session / pairing flow
- Same rich feature set (media, group tools, anti-link, auto-replies, etc.)
- **Plus real buttons** for a smoother mobile experience

The bot is already hosted and ready for connection at:

### 👉 **https://v2.creepytech.org**

Just open that link, generate your session / pair your number, and you are live. No need to self-host unless you want full control of the code.

---

## 🌟 Why V2 exists (long explanation)

Many people loved the button interface of earlier CreepyTech releases. When the project evolved toward V3, some of the button flows were simplified or replaced with list messages / pure text for compatibility and cleaner code. A large part of the community still preferred the tactile “tap a button” style, especially on Android and in groups where typing long commands is annoying.

V2 was therefore kept (and polished) as the **button-first** edition:

1. **Familiarity** – If you already know how to use any modern CreepyTech / Danny Tech bot, V2 will feel instantly natural.
2. **Buttons everywhere it makes sense** – Main menu, sub-menus, yes/no confirmations, feature toggles, etc. appear as real WhatsApp buttons.
3. **Still modern under the hood** – Multi-device support, pairing code, solid anti-spam / anti-link, media tools, and the usual CreepyTech quality.
4. **Hosted option** – Because the official instance is already running at `v2.creepytech.org`, most users never need to touch a terminal or a panel. Just pair and go.
5. **Self-host ready** – If you prefer your own VPS, Railway, Render, Bot-Hosting, Replit, Codespaces, etc., the full source is here so you can deploy it yourself.

This dual approach (official hosted link + open source) is intentional: casual users get zero friction, power users get full control.

---

## 🚀 Key Features (detailed)

- **Interactive Buttons** – The defining feature of V2. Menus and many replies come as tappable buttons instead of pure text.
- **Multi-Device WhatsApp** – Works with the official multi-device protocol. Pair once and use on phone + linked devices.
- **Session / Pairing** – Generate a session ID or use the pairing code flow through the official site or your own deployment.
- **Group Management** – Anti-link, anti-spam, welcome messages, promote/demote helpers, and more.
- **Media Tools** – Stickers, image/video conversion, audio handling, download helpers, etc.
- **Auto-Reply & Custom Responses** – Easy to customize how the bot reacts to certain messages or triggers.
- **Lightweight & Efficient** – The codebase is kept practical so it runs well even on modest hosting plans.
- **Fully Customizable** – Change owner numbers, prefixes, responses, and feature flags in the settings files.
- **Already Hosted** – Official live instance at **https://v2.creepytech.org** so you can start using it in minutes.

---

## 🛠️ How to Get Started (step-by-step)

### Option A – Easiest (Recommended for most people)

1. Go to the official hosted bot:  
   **https://v2.creepytech.org**
2. Follow the on-screen instructions to generate a session or pair your WhatsApp number (pairing code or QR depending on the current flow).
3. Once paired, the bot is ready. Open WhatsApp and start using the commands / button menus.

That is literally it for the majority of users. No GitHub, no VPS, no Node installation required.

### Option B – Self-host / Deploy the source

If you want to run your own copy:

1. **Fork this repository** (click the Fork button at the top right of this page).
2. **Star the repo** – it helps the project stay visible and motivates continued updates.
3. Download the ZIP or clone with Git:
   ```bash
   git clone https://github.com/Daniel432-gift/CREEPY_MD-V2.git
   cd CREEPY_MD-V2
   ```
4. Install dependencies (Node.js required):
   ```bash
   npm install
   ```
5. Configure your settings (owner number, prefix, etc.) in the appropriate config / settings files.
6. Generate a session (use the official session site or the pairing method provided in the project).
7. Deploy to any of the platforms below or run locally with `npm start` / the Procfile / Dockerfile.

---

## 📋 Deployment Options

You can deploy CREEPY_MD-V2 on almost any modern hosting platform that supports Node.js:

| Platform          | Notes                                      | Quick Link / Tip                          |
|-------------------|--------------------------------------------|-------------------------------------------|
| Official Hosted   | Zero setup – just pair                     | https://v2.creepytech.org                 |
| Bot-Hosting.net   | Popular for WhatsApp bots                  | Use their panel + this repo               |
| Render            | Free tier available, easy Git deploy       | Connect this GitHub repo                  |
| Railway           | Simple + good free credits                 | Deploy from GitHub                        |
| Replit            | Browser-based, good for testing            | Import from GitHub                        |
| Google Cloud / Shell | More advanced, full control             | Use Cloud Shell or a VM                   |
| Codespaces        | GitHub’s own cloud IDE                     | Open this repo in Codespaces              |
| VPS (Ubuntu etc.) | Full control, Docker or PM2 recommended    | Clone + `npm install` + process manager   |

A `Dockerfile` and `Procfile` are included so container and Heroku-style platforms work out of the box.

---

## 📱 Session / Pairing

The recommended way is still the official flow:

- Visit **https://v2.creepytech.org**
- Or use the session generation page linked from CreepyTech resources

Once you have the session credentials, place them where the bot expects them (usually a `session` folder or the path defined in the settings). The exact method is documented inside the project files and on the hosting site.

---

## ⚙️ Configuration Notes

- Owner numbers, bot name, prefixes, and feature toggles live in the settings / config files.
- Anti-link, auto-reply databases, and other runtime data are stored under the `database` folder.
- Media assets and temporary files go into the various media directories.
- Always keep your session private. Never commit real session files to a public repository.

---

## 🤝 Community & Support

- Join the official CreepyTech / Danny Tech WhatsApp channels and groups for updates, help, and new features.
- Star and fork this repository so you stay notified of updates.
- If you find bugs or want improvements, open an issue or reach out through the official channels.

---

## 🎉 Credits & Thank You

- **Danny Tech / CreepyTech** – Creator and maintainer
- Everyone who forks, stars, deploys, and gives feedback
- The wider WhatsApp bot community that keeps these projects useful and fun

Your support (stars, forks, and sharing the link **https://v2.creepytech.org**) is what keeps CREEPY_MD alive and improving.

---

<p align="center">
  <b>CREEPY_MD-V2 – Like V3, but with buttons.</b><br>
  Official hosted bot: <a href="https://v2.creepytech.org">https://v2.creepytech.org</a><br><br>
  🌟 Fork it • Star it • Pair it • Enjoy it 🌟
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="rainbow" />
</p>
