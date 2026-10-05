# LaoYing Toolkit

[![Latest release](https://img.shields.io/github/v/release/Lypc233/LaoYing-Toolkit?style=flat-square&color=e0783b&label=Release)](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest)
[![Total downloads](https://img.shields.io/github/downloads/Lypc233/LaoYing-Toolkit/total?style=flat-square&color=e0783b&label=Downloads)](https://github.com/Lypc233/LaoYing-Toolkit/releases)
![Windows 10 / 11 x64](https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-606060?style=flat-square)

![LaoYing Toolkit](assets/banner.png)

[简体中文](README.md) · **English**

LaoYing Toolkit is a performance tuning utility for Windows gaming PCs, developed and maintained by [老嘤评测](https://space.bilibili.com/520490678). It is free to use. This repository provides downloads, release notes and issue tracking.

## Features

- **CPU scheduling**: Set per-game or per-process core assignments, preferred cores and scheduling modes, with support for AMD CCDs and Intel P-core / E-core groups.
- **System optimization**: Manage common Windows options, power plans, startup apps and services.
- **DLSS profiles**: Set a game's DLSS model preset, quality mode and scaling ratio without replacing its DLL files.
- **AMD memory tuning**: Adjust frequency, voltage and timings, with profile import/export and backup restoration.
- **PBO tuning**: VID alignment, automatic per-core Curve Optimizer tuning, and CO / FMax settings and saved records.

DLSS, memory tuning and PBO require compatible hardware, firmware and drivers. Available options depend on the application's detection results.

## Download

**[GitHub Releases](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest)** · **[Quark Drive](https://pan.quark.cn/s/01f35cf699fa)**

1. Download the `.exe` under **Assets** on the release page, rather than the `Source code` archives.
2. Keep the executable in a permanent folder, launch it and approve the administrator prompt.
3. Windows 10 / 11 x64 is required. Official builds are distributed as a single executable with .NET included.

## Usage

- **CPU scheduling**: Create a rule for the game's actual executable, select its core range and enable the rule. Start with the default V4 mode.
- **DLSS**: Select the game's executable, then choose a model preset and quality mode. Results depend on the game and graphics driver.
- **Memory / PBO**: Start with the [video tutorials (Chinese)](https://space.bilibili.com/520490678), keep your original settings and make gradual changes. Follow the PBO page to prepare the required tools; the PawnIO driver must be installed separately.
- **Background operation**: Scheduling continues while the app is minimized to the tray. To stop it, choose “退出并恢复调度状态” (Exit and restore scheduling state) from the tray menu.
- **Updates**: Open “设置 → 软件更新” (Settings → Software updates). Before replacing the EXE manually, exit the toolkit normally from the tray menu.

Overclocking and undervolting can cause instability. A successful write does not confirm stability; test the settings on your own hardware and games.

## Community and feedback

- Video tutorials: [老嘤评测 on Bilibili](https://space.bilibili.com/520490678) (Chinese)
- QQ group: `1128807301`
- Bug reports: [GitHub Issues](https://github.com/Lypc233/LaoYing-Toolkit/issues)

Please include the toolkit version, hardware models, Windows version, steps to reproduce and relevant screenshots when reporting a problem.
