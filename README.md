<h1 align="center">⌨️ Unity3D New InputField Keyboard For VR</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Unity-3D-blue?logo=unity" alt="Unity">
  <img src="https://img.shields.io/badge/VR-Pico4-orange" alt="Pico4">
  <img src="https://img.shields.io/badge/platform-Android-green?logo=android" alt="Android">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen" alt="License">
</p>

<p align="center">
  <a href="#-概述--overview">📖 概述</a> •
  <a href="#-特性--features">✨ 特性</a> •
  <a href="#-截图--screenshots">📸 截图</a> •
  <a href="#-环境要求--requirements">📋 环境要求</a> •
  <a href="#-快速开始--quick-start">🚀 快速开始</a> •
  <a href="#-已知问题--known-issues">⚠️ 已知问题</a> •
  <a href="#-致谢--credits">🙏 致谢</a> •
  <a href="#-许可证--license">📄 许可证</a>
</p>

---

## 📖 概述 / Overview

解决 Unity3D 系统自带 `InputField` 在 **VR 程序（APK 格式）** 中，通过 UI 射线点击触发字符输入功能失效的问题。

本包提供了一个 **VR 虚拟键盘** 和一个 **自制 InputField 组件**，开箱即用。

> Fixes the issue where Unity's built-in `InputField` fails to trigger character input via UI ray clicks in **VR applications (APK format)**.
>
> This package includes a **VR virtual keyboard** and a **custom InputField component** — ready to use out of the box.

---

## ✨ 特性 / Features

- 🎮 **VR 虚拟键盘** — 支持数字、大小写字母输入
- 🧩 **自制 InputField** — 替代原生组件，兼容 VR 射线交互
- 🔌 **零依赖** — 不依赖任何第三方插件或包
- 🎯 **即拖即用** — 导入包后，直接把预制体拖入场景
- ✅ **实机验证** — 已在 Pico4 上安装并测试通过

| 功能           | 状态               |
|---------------|--------------------|
| 数字输入       | ✅ 已支持          |
| 大写字母输入   | ✅ 已支持          |
| 小写字母输入   | ✅ 已支持          |
| 符号输入       | ❌ 暂不支持        |

---

## 📸 截图 / Screenshots

<p align="center">
  <img src="https://user-images.githubusercontent.com/32610394/210243194-afb8d2cb-3f48-42fe-9cc7-2d25c8a1041d.png" width="45%" alt="VR Keyboard Preview" />
  <img src="https://user-images.githubusercontent.com/32610394/210244091-441fb4fc-35f4-499d-9658-b71b68efe94e.png" width="45%" alt="Pico4 Device" />
</p>

<p align="center"><em>VR 虚拟键盘界面 &nbsp;|&nbsp; Pico4 实机运行截图</em></p>

---

## 📋 环境要求 / Requirements

| 项目     | 说明                             |
|---------|----------------------------------|
| 引擎     | Unity3D                         |
| 平台     | Android (APK)                   |
| VR 设备  | Pico4 等支持射线交互的 VR 设备    |
| 额外组件 | XR Interaction Toolkit 的 `Tracked Device Graphic Raycaster`（按需添加） |

---

## 🚀 快速开始 / Quick Start

### 安装 / Installation

1. 下载本仓库的 [`WpzKeyboard.unitypackage`](./WpzKeyboard.unitypackage)
2. 在 Unity 中双击导入，或通过 `Assets > Import Package > Custom Package...` 导入
3. 导入完成后，在 `Assets` 中找到预制体

### 使用 / Usage

1. 将预制体 `WpzKeyboard` 拖入你的场景
2. 为 Canvas 添加 **XR UI 交互组件**（如 XR Interaction Toolkit 的 `Tracked Device Graphic Raycaster`）
3. 运行场景，使用 VR 手柄射线点击输入框即可唤起键盘

```csharp
// 无需额外代码，预制体已预置所有交互逻辑
// No extra code needed — all interaction logic is pre-configured
```

---

## ⚠️ 已知问题 / Known Issues

- 键盘功能尚不完善，仅支持**数字**和**大小写字母**输入
- 暂无符号键、特殊字符支持
- 键盘美术素材来自第三方资源（见下方致谢）

> The keyboard currently supports only digits, uppercase and lowercase letters. Symbols and special characters are not yet available.

---

## 🙏 致谢 / Credits

键盘 UI 素材来源：

> [CSDN - Unity VR 键盘实现](https://blog.csdn.net/qq_40401591/article/details/120532647)

感谢原作者的分享。

---

## 📄 许可证 / License

本项目使用 [MIT License](./LICENSE) 开源许可。
