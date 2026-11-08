# 🎚️ Windows Audio Volume Controller

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=26,4,17&height=210&section=header&text=Windows%20Audio%20Volume%20Controller&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Total%20Control%20Over%20Every%20Sound%20on%20Windows&descAlignY=56&descSize=17" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.7.0-7209B7?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%2010%20%7C%2011-3A0CA3?style=for-the-badge&logo=windows11&logoColor=white)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/license-MIT-4361EE?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Size](https://img.shields.io/badge/size-%3C%205%20MB-4CC9F0?style=for-the-badge&logo=databricks&logoColor=white)](https://github.com)

<br/>

### 🎛️ A powerful per-app volume mixer and audio controller for Windows

*🎚️ Per-App Volume • 🔊 Device Switching • ⌨️ Hotkeys • 🎨 Themes*

<br/>

<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD-7209B7?style=for-the-badge&logo=download&logoColor=white&labelColor=560A8A" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-3A0CA3?style=for-the-badge&logo=rocket&logoColor=white&labelColor=2A0780" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/📚_DOCS-4361EE?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=2F4BC4" alt="Docs" height="45"/>
</a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Windows Audio Volume Controller** is a lightweight desktop utility that gives you **full control over audio on Windows** — far beyond what the built-in volume mixer offers. Set custom volumes for every app, switch output devices with a hotkey, create per-scenario audio profiles, and see exactly what's playing.

It replaces the frustrating Windows volume mixer with something clean, fast, and actually pleasant to use.

> 💡 **Perfect for:** Gamers, streamers, remote workers, and anyone juggling multiple audio devices and apps.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🎚️ **Per-App Volume** | 🔊 **Device Switching** | ⌨️ **Hotkeys** |
|:---:|:---:|:---:|
| Independent volume<br/>for every app | Switch between<br/>headphones & speakers | Global shortcuts<br/>for all actions |

| 🎨 **Profiles** | 📊 **Visual Feedback** | 🌙 **Dark Mode** |
|:---:|:---:|:---:|
| Save & restore<br/>audio setups | VU meters &<br/>level indicators | System theme<br/>integration |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎯 **Beyond Windows** | Controls audio for apps that the default mixer ignores |
| ⚡ **Tiny & Fast** | Under 5 MB, instant startup, near-zero CPU usage |
| 🎨 **Clean UI** | Modern design with dark mode and smooth animations |
| 🧩 **Per-App Profiles** | Save different configurations for gaming, streaming, meetings |
| ⌨️ **Hotkey Everything** | Adjust any volume, device, or profile without leaving your game |
| 🔌 **No Drivers** | Uses native Windows audio APIs — no kernel drivers, no risks |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 App Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🎚️  Audio Volume Controller  v2.7.0             ║
╠══════════════════════════════════════════════════╣
║  🔊 Output: Headphones (Realtek HD Audio)        ║
║  ──────────────────────────────────────────      ║
║  Master Volume                                   ║
║  ▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬░░░░░░░░  65%                   ║
║                                                  ║
║  Per-App Mixer                                   ║
║  ──────────────────────────────────────────      ║
║  🎮 Steam        ▬▬▬▬▬▬▬▬▬▬▬▬░░░░  80%          ║
║  🌐 Chrome       ▬▬▬▬▬▬▬▬░░░░░░░░  45%          ║
║  🎵 Spotify      ▬▬▬▬▬▬▬▬▬▬▬▬▬░░  70%          ║
║  💬 Discord      ▬▬▬▬▬▬▬▬▬▬░░░░░░  55%          ║
║  🎬 OBS Studio   ▬▬▬▬▬▬▬▬▬▬▬▬▬▬  90%           ║
║                                                  ║
║  🎨 Profiles: 🎮 Gaming  🎙️ Streaming  📞 Work   ║
║  ⌨️ Hotkeys active   🌙 Dark mode   🚀 1.2% CPU  ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🎚️ windows-audio-volume-controller/
├── 🎯 src/
│   ├── audio/                 # WASAPI integration
│   │   ├── session-manager.cs
│   │   └── device-manager.cs
│   ├── ui/                    # WPF interface
│   │   ├── main-window.xaml
│   │   └── themes/
│   ├── hotkeys/               # Global hotkey handling
│   └── profiles/              # Save/restore audio setups
├── 🎨 assets/                 # Icons & sounds
├── 🧪 tests/                  # Unit & UI tests
└── 📖 docs/                   # Setup & hotkey reference
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%208-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=windows&logoColor=white)
![WASAPI](https://img.shields.io/badge/WASAPI-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Windows](https://img.shields.io/badge/Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows11&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new hotkey or profile type?

<div align="center">

<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-7209B7?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/SeIe1lg8tHP8TC9bF">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-4CC9F0?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### 🎚️ Made with 🔊 by the Windows Audio Team

*If this tool gave you control over your sound — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=26,4,17&height=120&section=footer" width="100%"/>

</div> 
