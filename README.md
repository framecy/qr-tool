# 📱 纯前端二维码小工具 (QR Code Tool)

> 一个轻量、高颜值、**完全纯前端实现**的二维码生成与识别工具。

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Static Badge](https://img.shields.io/badge/Pure-Frontend-purple) ![Static Badge](https://img.shields.io/badge/Privacy-Safe-green)

这是一个基于 HTML5、Tailwind CSS 和 JavaScript 构建的单页应用 (SPA)。它无需后端服务器支持，所有数据处理均在浏览器本地完成，确保您的数据隐私安全。

---

## ✨ 核心功能

### 1. 🎨 二维码生成 (Generate)
* **多类型支持**：支持文本、网址、WiFi 配置信息等任意字符串。
* **即时预览**：输入内容后点击生成，立即显示高清二维码。
* **一键保存**：支持将生成的二维码下载为 PNG 图片。
* **高容错率**：默认使用 M 级容错，确保二维码清晰易扫。

### 2. 📷 二维码识别 (Scan)
* **多方式导入**：
    * 📂 **本地上传**：点击选择图片文件。
    * 🖱️ **拖拽上传**：直接将图片拖入识别区域。
    * 📋 **剪贴板粘贴**：支持 **Ctrl+V** 直接粘贴截图或复制的图片（支持 PDF 截图粘贴），体验极佳。
* **结果复制**：识别成功后，一键复制解析内容。

### 3. 💅 UI 与交互
* **薰衣草紫主题**：采用潘通流行色（Digital Lavender）配色，视觉清新治愈。
* **响应式设计**：
    * **移动端**：全屏沉浸式体验，适配各种手机屏幕。
    * **桌面端**：精致的圆角卡片布局，固定尺寸，防止布局塌陷。
* **动画交互**：平滑的 Tab 切换、按钮悬停反馈、加载动画。

---

## 🛠 技术栈

本项目为**纯静态页面**，无任何构建工具依赖，开箱即用。

* **核心结构**：HTML5
* **样式框架**：[Tailwind CSS](https://tailwindcss.com/) (通过 CDN 引入)
* **脚本语言**：原生 JavaScript (ES6+)
* **依赖库**：
    * `qrcode.js` (v1.0.0) - 用于二维码生成
    * `jsQR` (v1.4.0) - 用于二维码解析

---

## 🚀 快速开始

### 本地运行
1.  克隆或下载本仓库。
2.  直接双击打开 `index.html` 文件即可使用。
    * *注意：为了获得最佳体验（特别是图片跨域或下载功能），建议使用 Live Server 或简单的 HTTP 服务器运行。*

### 使用 Python 快速启动本地服务器
```bash
# 进入项目目录
cd qr-tool

# 启动服务器 (Python 3)
python -m http.server 8000
