# FakeDAT

🧰 **FakeDAT** 是一个面向 **俄服剑灵Blade & Soul（BNS）** 的 **DAT** 解包/编辑/回包工具，基于 **Tauri + React + Rust** 构建
| ![](https://github.com/user-attachments/assets/a55aaafc-5ea8-4763-8350-88cf4d2d081c) | ![](https://github.com/user-attachments/assets/dea62e98-e3c6-4b28-a296-a899b7cdf942) |
| --- | --- |

---

## ✨ 功能与作用

- 🧩 **一键解包/回包**：针对 `xml.dat` 提供解包与重打包流程，降低手工成本。
- 🗂️ **文件树浏览**：解包后以目录树方式展示文件结构，快速定位目标文件。
- 📝 **内置编辑器**：支持打开/编辑 XML 等文本内容，保存后即可回包。
- 🔍 **扫描模式**：可对指定目录进行快速扫描，避免误操作工作区。
- 📣 **状态与提示**：关键流程有提示、进度与错误反馈。
- 🔒 **AES_KEY**：**FakeDAT** 已内置 **AES_KEY**，简单测试可用于俄服（现新加坡服），但不保证能回包后可以正确加载
- 🛑 **特别提醒**：由于本工具是基于 **AI开发并驱动**，且开发环境为 **网吧**，所以无测试对象，有问题留言

---

## 🚀 主要特点

- ⚡ **性能优先**：Rust 后端负责解包/回包，速度快、稳定性高。
- 🧩 **独立 EXE**：便携式独立 EXE 程序，无垃圾产出。
- 🧯 **出错才写日志**：仅在程序异常时输出日志，干净可控。
---

## 🚀 下载地址

- **GitHUb原生地址👉**：[FakeDAT v0.1.0.rar](https://github.com/Coming404/FakeDAT/releases/download/0.1.0/FakeDAT.v0.1.0.rar)
- **镜像加速地址👉**：[FakeDAT v0.1.0.rar](https://hk.gh-proxy.org/https://github.com/Coming404/FakeDAT/releases/download/0.1.0/FakeDAT.v0.1.0.rar)
---

## ✅ 环境要求

- Windows 10 x86_x64
- WebView2 Runtime（Windows 10 通常自带，不足时手动安装）

---

## 🧾 日志

仅在程序运行出错时才会生成日志（和 EXE 同目录）：

- `fakedat_startup.log`：后端启动/运行异常
- `fakedat_frontend.log`：前端运行时错误

---

## 📝 许可证

HELLO，MOTHER FUCK.
