# Unity3D New InputField Keyboard For VR

解决 Unity3D 系统自带 `InputField` 在 **VR 程序（APK 格式）** 中，通过 UI 射线点击触发字符输入功能失效的问题。

本包提供了一个 **VR 虚拟键盘** 和一个 **自制 InputField 组件**，开箱即用。

> Fixes the issue where Unity's built-in `InputField` fails to trigger character input via UI ray clicks in **VR applications (APK format)**.
> This package includes a **VR virtual keyboard** and a **custom InputField component** — ready to use out of the box.

---

## 特性 / Features

- **VR 虚拟键盘** — 支持数字、大小写字母输入
- **自制 InputField** — 替代原生组件，兼容 VR 射线交互
- **零依赖** — 不依赖任何第三方插件或包
- **即拖即用** — 导入包后，直接把预制体拖入场景
- **实机验证** — 已在 Pico4 上安装并测试通过

---

## 截图 / Screenshots

![VR Keyboard Preview](https://user-images.githubusercontent.com/32610394/210243194-afb8d2cb-3f48-42fe-9cc7-2d25c8a1041d.png)

Pico4 实机运行：

![Pico4 Device](https://user-images.githubusercontent.com/32610394/210244091-441fb4fc-35f4-499d-9658-b71b68efe94e.png)

---

## 使用 / Usage

1. 下载 [`WpzKeyboard.unitypackage`](./WpzKeyboard.unitypackage)
2. 在 Unity 中通过 `Assets > Import Package > Custom Package...` 导入
3. 将预制体 `WpzKeyboard` 拖入场景
4. 为 Canvas 添加 **XR UI 交互组件**（如 XR Interaction Toolkit 的 `Tracked Device Graphic Raycaster`）
5. 运行即可使用

---

## 已知问题 / Known Issues

- 仅支持数字和大小写字母输入，暂无符号键
- 键盘 UI 素材来自第三方（见下方致谢）

---

## 致谢 / Credits

键盘 UI 素材来源：[CSDN - Unity VR 键盘实现](https://blog.csdn.net/qq_40401591/article/details/120532647)

---

## 许可证 / License

[MIT](./LICENSE)
