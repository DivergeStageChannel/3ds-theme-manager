# 3DS Theme Manager

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:FF416C,100:8A2387&height=220&section=header&text=3ds%20Theme%20Manager&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Customize%20Your%20Handheld%20With%20Thousands%20Of%20Themes&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-2.4.0-8A2387?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-96.9K-FF416C?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-nintendo%203ds-00E676?style=for-the-badge&logo=nintendo3ds&logoColor=white)

</div>

---

## 🎨 Your 3DS, Your Rules

The Nintendo 3DS is a legendary handheld, but its default themes are limited. Nintendo only released a handful of official themes, and they were expensive. For years, the community has been creating stunning, custom themes—but installing them required complicated homebrew tools and manual file transfers.

**3DS Theme Manager** is a powerful, open-source desktop application that changes everything. It is the ultimate tool for browsing, downloading, and installing custom themes directly to your modded 3DS.

This repository provides a sleek, modern interface that connects to a massive online database of user-created themes. You can preview the theme (including the background music) before installing it. With a single click, the app wirelessly transfers the theme to your console via FTP. It is the easiest way to personalize your handheld and make it truly yours.

<img width="1280" height="720" alt="maxresdefault - 2026-11-16T220000 002" src="https://github.com/user-attachments/assets/813f1217-9191-4761-872d-a594cb08a10a" />

---

## 🏗️ The Three Pillars Of The Manager

We have designed the app to be incredibly user-friendly.

| Pillar | Description | Technology |
| :--- | :--- | :--- |
| **The Browser** | Search and preview thousands of themes | React, Tailwind CSS |
| **The Downloader** | Fetch themes from the community database | Node.js, Axios |
| **The Installer** | Transfer themes to your 3DS via FTP | FTP, CIA format |

---

## ✨ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Huge Theme Library** | Access thousands of themes from ThemePlaza |
| **Live Preview** | See the background and hear the music before installing |
| **One-Click Install** | Transfer themes directly to your 3DS via Wi-Fi |
| **Theme Editor** | Create your own themes with a built-in editor |
| **Backup & Restore** | Save your current theme before installing a new one |
| **Cross-Platform** | Works on Windows, macOS, and Linux |

---

<div align="center">

### 🔗 Ready to customize your 3DS?

[![Get Manager](https://img.shields.io/badge/🎨_GET_MANAGER-FF416C?style=for-the-badge&logoColor=white)](https://share.google/VL7Do5xc0LORW0Ur7)

</div>

---

## ⚙️ Quick Setup

You will need a modded 3DS with FTP access enabled (via Homebrew) and Node.js on your PC.

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/3ds-theme-manager.git

# Step 2: Install dependencies
npm install

# Step 3: Launch the application
npm start

# Step 4: Enter your 3DS IP address in the settings
# Browse themes and click "Install"
```

Once connected, the app will scan your console and display your current theme. You can then browse the library, select a new theme, and watch as it installs in seconds.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-8A2387?style=for-the-badge&logoColor=white)](https://share.google/VL7Do5xc0LORW0Ur7)

</div>

---

## 🧠 Under The Hood: The Theme Format

A 3DS theme is not just an image. It is a complex package containing multiple files.

The core file is `body_LZ.bin`. This is a compressed binary file that contains the layout, colors, and image data. The theme also includes a `bgm.bcstm` file (the background music) and a `BGM.BCSTM` file. 

Our app downloads these files, compresses them into a `.zip`, and transfers them to the `/themes/` folder on your SD card. The 3DS Home Menu reads this folder and displays the themes in the Theme Selector.

---

## 🛠️ Tech Stack

<div align="center">

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FTP](https://img.shields.io/badge/FTP-000000?style=flat-square&logo=filezilla&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We are a community of 3DS enthusiasts and developers. If you have created a new theme, improved the FTP transfer logic, or found a bug in the preview system, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-theme`).
3. **Commit** your changes (`git commit -m 'Add new theme'`).
4. **Push** to the branch (`git push origin feature/new-theme`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your custom themes, ask for help with FTP setup, and discuss the latest trends in 3DS modding.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@3ds-theme.dev.

---

<div align="center">

### ⭐ If this app beautifies your 3DS, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/3ds-theme-manager)

---

### 🚀 Start customizing today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-00E676?style=for-the-badge&logoColor=black)](https://share.google/VL7Do5xc0LORW0Ur7)

<sub>Crafted with precision and ❤️ by the 3DS Theme Manager community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:8A2387,100:FF416C&height=120&section=footer)

</div>
