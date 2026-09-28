# LaoYing Toolkit

[![最新版本](https://img.shields.io/github/v/release/Lypc233/LaoYing-Toolkit?style=flat-square&color=e0783b&label=Release)](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest)
[![下载次数](https://img.shields.io/github/downloads/Lypc233/LaoYing-Toolkit/total?style=flat-square&color=e0783b&label=Downloads)](https://github.com/Lypc233/LaoYing-Toolkit/releases)
![Windows 10 / 11 x64](https://img.shields.io/badge/Windows-10%20%2F%2011%20x64-606060?style=flat-square)

![LaoYing Toolkit](assets/banner.png)

**简体中文** · [English](README_EN.md)

老嘤超频优化工具箱，一款面向 Windows 游戏环境的性能调校工具，由 [老嘤评测](https://space.bilibili.com/520490678) 制作与维护。软件免费使用，本仓库提供下载、更新说明和问题反馈，不提供工具箱源码。

## 功能

- **核心调度**：按游戏或进程设置核心范围、优先核心和调度模式，支持 AMD CCD、Intel 大小核分区。
- **系统优化**：管理常用系统选项、电源计划、启动项和服务。
- **DLSS 模型**：设置游戏的 DLSS 模型预设、画质模式和缩放比例，无需替换游戏 DLL。
- **AMD 内存超频**：调整频率、电压与时序，支持配置导入导出和备份恢复。
- **PBO 调校**：VID 对齐、自动分核心负压，以及 CO / FMax 设置与记录管理。

DLSS、内存超频和 PBO 需要对应硬件、固件与驱动支持，以软件内检测结果为准。

## 下载

**[GitHub 下载](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest)** · **[夸克网盘](https://pan.quark.cn/s/01f35cf699fa)**

1. 从发布页的 **Assets** 下载 `.exe`，不要下载 `Source code`。
2. 将程序放到固定文件夹，运行后按提示授予管理员权限。
3. 支持 Windows 10 / 11 x64，正式包为单文件版，无需另装 .NET。

## 使用说明

- **核心调度**：为游戏实际运行的 EXE 建立规则，选择核心范围并启用，可先用默认 V4 模式。
- **DLSS**：选择游戏 EXE，再设置模型与画质模式。实际效果取决于游戏和显卡驱动。
- **内存 / PBO**：建议先看 [视频教程](https://space.bilibili.com/520490678)，保留原配置后逐步调整。PBO 所需工具按页面提示准备，PawnIO 驱动需要单独安装。
- **后台运行**：最小化到托盘后调度仍会继续；停止调度请用托盘菜单中的“退出并恢复调度状态”。
- **更新**：进入“设置 → 软件更新”；手动替换 EXE 前，请先从托盘正常退出工具箱。

超频、降压可能导致不稳定。写入成功不代表稳定，请结合自己的硬件和游戏实测。

## 交流与反馈

- 视频教程：[B 站 · 老嘤评测](https://space.bilibili.com/520490678)
- QQ 交流群：`1042550392`
- 问题反馈：[GitHub Issues](https://github.com/Lypc233/LaoYing-Toolkit/issues)

反馈时请附上工具箱版本、硬件型号、Windows 版本、复现步骤和必要截图。
