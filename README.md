# 📱 纯前端二维码小工具 (QR Code Tool)

<img width="438" height="600" alt="img1" src="data:image/png;base64,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" />



> 一个轻量、高颜值、**完全纯前端实现**的二维码生成与识别工具。无需后端服务器，保障隐私安全。

这是一个基于 HTML5、Tailwind CSS 和 JavaScript 构建的单页应用 (SPA)。它设计简洁，不仅支持二维码的快速生成，还具备强大的识别功能，特别优化了从剪贴板粘贴截图的体验。

## ✨ 核心功能

### 1. 🎨 二维码生成 (Generate)

* ​**多类型支持**​：支持文本、网址、WiFi 配置信息等任意字符串生成二维码。
* ​**即时预览**​：输入内容后点击生成，立即显示高清二维码。
* ​**一键保存**​：生成的二维码可直接下载保存为 PNG 图片。
* ​**视觉优化**​：定制化的 UI 风格，操作流畅。

### 2. 📷 二维码识别 (Scan)

* ​**多方式导入**​：
  * 📂 ​**本地上传​**​：点击虚线框选择图片文件。
  * 🖱️ ​**拖拽上传​**​：支持将图片直接拖入识别区域。
  * 📋 ​**剪贴板粘贴 (强力推荐)**​：支持 **Ctrl+V** 直接粘贴截图或复制的图片（完美支持 PDF 截图粘贴），自动读取并识别。
* ​**结果处理**​：识别成功后显示解析内容，并提供一键复制功能。

### 3. 💅 UI 与交互

* ​**薰衣草紫主题**​：采用潘通流行色（Digital Lavender）配色，视觉清新治愈。
* ​**响应式设计**​：
  * ​**移动端**​：H5 自适应，全屏沉浸式体验，无滚动条干扰。
  * ​**桌面端**​：精致的圆角卡片布局，固定尺寸，防止页面塌陷或变形。
* ​**动画交互**​：平滑的 Tab 切换、按钮悬停反馈、加载动画及文件名显示。

## 🛠 技术栈

本项目为​**纯静态页面**​，无任何构建工具依赖，开箱即用。

* ​**核心结构**​：HTML5
* ​**样式框架**​：[Tailwind CSS](https://tailwindcss.com/ "null") (CDN 引入)
* ​**脚本语言**​：原生 JavaScript (ES6+)
* ​**依赖库**​：
  * `qrcode.js` (v1.0.0) - 用于生成二维码
  * `jsQR` (v1.4.0) - 用于解析二维码图片

## 🚀 快速开始

### 方法一：直接运行

1. 克隆或下载本仓库。
2. 直接双击打开 `index.html` 文件即可使用。
   * *注意：某些浏览器可能会限制本地文件的图片跨域或下载功能，建议使用方法二。*

### 方法二：本地服务器 (推荐)

如果您安装了 Python，可以在项目目录下运行：

```
# 进入项目目录
cd qr-tool

# 启动服务器 (Python 3)
python -m http.server 8000
```

然后在浏览器访问 `http://localhost:8000`。


## 🔒 隐私声明

* ​**本地处理**​：本项目所有逻辑（生成与识别）均在浏览器端运行。
* ​**零上传​**​：您输入的文本、生成的二维码、上传/粘贴的图片**绝对不会**上传到任何远程服务器。
* ​**安全无忧**​：即便是敏感的配置信息（如 WiFi 密码、API Key），也可以放心使用。

## 📄 开源协议

MIT License
