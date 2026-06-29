<div align="center">

# Darwin Toolkit

### A powerful, all-in-one Windows performance & system optimization toolkit for gamers and power users.

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6?style=flat-square&logo=windows&logoColor=white)](#)
[![Framework](https://img.shields.io/badge/.NET%20Framework-4.8-512BD4?style=flat-square&logo=dotnet&logoColor=white)](#)
[![Built with](https://img.shields.io/badge/Built%20with-C%23%20%2F%20WPF-239120?style=flat-square&logo=csharp&logoColor=white)](#)
[![Version](https://img.shields.io/badge/Version-1.0.0-00F0FF?style=flat-square)](https://github.com/f4rukemre/darwin-toolkit/releases)
[![License](https://img.shields.io/badge/License-MIT-8A2BE2?style=flat-square)](LICENSE)

</div>

---

## ⚡ Overview

**Darwin Toolkit** is a portable Windows desktop application that brings system tuning, debloating, software management and per-game optimization together in one clean, neon-styled interface. It is built for people who want their PC fast, lean and ready for competitive play — without digging through dozens of registry keys and settings menus.

Everything is **one click away**, every system tweak is logged in a live terminal feed, and the most important changes are **reversible**.

> ⚠️ Darwin Toolkit makes real changes to your system (registry, services, power plans, installed apps). Please read the [Safety & Disclaimer](#-safety--disclaimer) section before use.

---

## ✨ Features

### 🖥️ Dashboard
- Live **system overview** — CPU, GPU, RAM and OS at a glance
- **One-Click Boost** — instantly frees up RAM and trims background load
- **Live Monitor** — real-time CPU & RAM graphs
- Quick actions: clear RAM standby, enable Ultimate Performance, wipe temp files
- **Performance Mode** for a full system surge before a session

### 🎯 System Tweaks
- Input-lag / latency reduction & CPU core-parking optimization
- Disable Xbox Game Bar, Game DVR and background capture
- Remove **Widgets, News feed and Start-menu advertising**
- Focus mode — silence notifications during gameplay
- **Network & Ping** optimization (Nagle off, throttling off) — *with a clear, reversible warning*
- **Privacy hardening** — disable telemetry, advertising ID and activity history
- **Windows Timer Resolution** tuning (Windows 11)
- An **automatic restore point** is created before the first change

### 📦 Software Center
- Install **50+ popular apps** silently via Windows Package Manager (winget)
- Categories: Game Clients, Browsers, Streaming/Broadcast, Comms, Monitoring, Media, Utilities, Peripherals
- Select what you want, hit install — Darwin handles the rest

### 🧹 Debloat
- Remove ~20 preinstalled consumer apps (Solitaire, Maps, Weather, News, Clipchamp, Teams, Copilot, Office Hub, and more)
- Xbox, Store and core system apps are **kept** — your browser data is **never touched**

### 🎮 My Games
- Auto-detects games from **Steam, Epic, Riot, EA and more**
- Pulls **official cover art** for Steam titles
- Per-game **Windows profile** (CPU priority, GPU preference, fullscreen-optimization, Game Mode)

### 🔄 Auto-Update
- Checks GitHub on launch and notifies you when a new version is released

---

## 📸 Screenshots

> <img width="1178" height="802" alt="sadasdasdas" src="https://github.com/user-attachments/assets/05074770-5576-4a63-a596-670f1752de92" />
<img width="1180" height="809" alt="sasda" src="https://github.com/user-attachments/assets/b5dec72f-124a-4a74-b470-56d85bff11e5" />
<img width="1177" height="805" alt="Ekran Alıntısı" src="https://github.com/user-attachments/assets/e827f203-6837-42d8-bece-b98778cc0010" />

---

## 📥 Download & Install

1. Go to the [**Releases**](https://github.com/f4rukemre/darwin-toolkit/releases) page.
2. Download the latest **`DarwinToolkitSetup.exe`**.
3. Run it and follow the installer. Darwin Toolkit requires **Administrator** rights to apply system changes.

> 🛡️ **SmartScreen note:** the app is not code-signed yet, so Windows may show *"Windows protected your PC."*
> Click **More info → Run anyway** to continue. (A code-signing certificate is planned.)

---

## 🧩 Requirements

- **Windows 10 or Windows 11** (64-bit)
- **.NET Framework 4.8** (the installer detects this and links you to the download if it's missing)
- Administrator privileges

---

## 🛠️ Building from Source

```bash
git clone https://github.com/f4rukemre/darwin-toolkit.git
```

1. Open **`DarwinToolkit.sln`** in **Visual Studio 2019 (16.3+) or 2022** with the *.NET desktop development* workload.
2. Switch the build configuration to **Release**.
3. **Build → Build Solution**.
4. The executable is produced at:
   `DarwinToolkit\bin\Release\net48\Darwin Toolkit.exe`

To build the installer, compile `installer\DarwinToolkit_Setup.iss` with [Inno Setup 6](https://jrsoftware.org/isdl.php).

---

## 🧱 Tech Stack

| | |
|---|---|
| **Language** | C# |
| **UI** | WPF (XAML) |
| **Runtime** | .NET Framework 4.8 |
| **Package manager** | Windows Package Manager (winget) |
| **Installer** | Inno Setup 6 |
| **Dependencies** | None — framework assemblies only (no external NuGet) |

---

## 🛡️ Safety & Disclaimer

Darwin Toolkit modifies Windows settings, the registry, services, power plans and installed applications.

- An **automatic system restore point** is created before the first tweak in a session.
- Most tweaks are **reversible** from within the app (toggle off to restore Windows defaults).
- The toolkit **avoids anti-cheat-risky changes** (it does not touch mitigations/VBS that can break Vanguard/EAC).
- Your **browser data, accounts and history are never deleted** — cleaning is limited to OS temp folders.

That said, this software is provided **"as is", without warranty of any kind**. You use it at your own risk. The author is not responsible for any data loss or system issues. Always make sure you understand a change before applying it.

---

## 👤 Author

**Darwin Development** — Faruk Emre Başer
🌐 [farukemrebaser.com](https://www.farukemrebaser.com) · 🐙 [@f4rukemre](https://github.com/f4rukemre)

---

<div align="center">

---

*Built with ⚡ for the competitive edge.*
