<div align="center">

<img src="assets/banner.svg" alt="LaoYing Toolkit · 老嘤超频优化工具箱" width="100%" />

<br />

[![最新版本](https://img.shields.io/github/v/release/Lypc233/LaoYing-Toolkit?style=flat-square&color=39b9dc&label=Release)](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest)
[![下载次数](https://img.shields.io/github/downloads/Lypc233/LaoYing-Toolkit/total?style=flat-square&color=39b9dc&label=Downloads)](https://github.com/Lypc233/LaoYing-Toolkit/releases)
![Windows 10 / 11](https://img.shields.io/badge/Windows-10%20%2F%2011-607d9b?style=flat-square)
[![B 站 · 老嘤评测](https://img.shields.io/badge/Bilibili-老嘤评测-fb7299?style=flat-square)](https://space.bilibili.com/520490678)

**把常用的游戏调校功能，放在一个工具箱里。**

[下载最新版](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest) · [夸克网盘](https://pan.quark.cn/s/01f35cf699fa) · [视频教程](https://space.bilibili.com/520490678) · [问题反馈](https://github.com/Lypc233/LaoYing-Toolkit/issues)

</div>

## 关于工具箱

LaoYing Toolkit（老嘤超频优化工具箱）是一款面向 Windows 游戏环境的性能调校工具，集中管理核心调度、系统优化、DLSS 模型、AMD 内存超频和 PBO 自动分核心负压。

由 **老嘤评测** 制作与维护。工具箱免费使用，本仓库用于软件下载、版本更新和问题反馈，不提供工具箱源码。

## 能做什么

| 功能 | 说明 |
| :--- | :--- |
| 🎯 核心调度 | 按游戏或进程设置核心范围、优先核心与调度模式，支持 AMD CCD 和 Intel 大小核分区。 |
| 🛠️ 系统优化 | 集中管理常用系统选项、电源计划、启动项和服务，按需调整。 |
| 🎮 DLSS 模型 | 为游戏设置 NVIDIA DLSS 模型预设、画质模式和缩放比例，无需替换游戏 DLL。 |
| 🧩 AMD 内存超频 | 查看与调整频率、电压、时序，支持配置导入导出及备份恢复。 |
| ⚡ PBO 调校 | VID 对齐、自动分核心负压调校，以及 CO / FMax 设置与记录管理。 |

具体功能以软件内的硬件检测和当前版本为准，DLSS、内存超频与 PBO 需要对应的平台支持。

## 下载与上手

1. 到 [Releases](https://github.com/Lypc233/LaoYing-Toolkit/releases/latest) 下载 **Assets 中的 `.exe`**；GitHub 下载慢可以用 [夸克网盘](https://pan.quark.cn/s/01f35cf699fa)。`Source code` 不是安装包。
2. 放到固定文件夹后运行，按提示授予管理员权限。正式包为 Windows 10 / 11 **64 位单文件版**，无需另装 .NET。
3. 想用核心调度，就为游戏的实际 EXE 建立规则，选择核心范围并启用。默认 V4 可先试用，效果以自己的游戏实测为准。
4. 更新时可进入 **设置 → 软件更新**；手动替换 EXE 前，先从托盘正常退出工具箱。

**最小化到托盘后调度仍在运行。** 想停止调度，请使用托盘菜单中的“退出并恢复调度状态”。

内存超频和 PBO 建议先看教程，保留原有配置，再逐步调整；参数能写入不代表已经稳定。PBO 按页面提示准备所需工具，PawnIO 驱动需要单独安装。

## 几个常见问题

<details>
<summary><b>旧版应用内更新失败怎么办？</b></summary>

部分旧版有下载大小限制，可从上面的 GitHub 或夸克入口手动下载新版，正常退出旧版后再替换。

</details>

<details>
<summary><b>调度后帧数没有提升，或者 Low 帧变差？</b></summary>

不同游戏和硬件的表现不一样。可以退回 V2 / V1 对比，先不要额外开启强绑选项，同时观察平均帧、Low 帧和帧时间。

</details>

<details>
<summary><b>为什么有的参数不能改？</b></summary>

功能是否可用取决于 CPU、主板固件、显卡驱动等条件。以页面检测结果为准，未提供的参数不会强行开放。

</details>

## 教程与交流

- **B 站：** [老嘤评测](https://space.bilibili.com/520490678)，使用教程和更新介绍都在这里。
- **QQ 交流群：** `1042550392`
- **反馈问题：** [提交 Issue](https://github.com/Lypc233/LaoYing-Toolkit/issues)，带上工具箱版本、硬件型号、系统版本和问题截图，方便排查。

---

<div align="center">
觉得好用的话，点个 ⭐ 支持一下。感谢大家的使用和反馈！
</div>
