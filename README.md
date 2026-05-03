<div align="center">
  <h1>🥽 VisionOS Pro Simulator</h1>
  <p>
    <strong>在网页上体验 Vision Pro 的空间交互</strong><br>
    支持眼动追踪 · 手部捏合 · 陀螺仪视差 · 实时壁纸切换
  </p>
  <p>
    <a href="https://visionosdemo.netlify.app">
      <img src="https://img.shields.io/badge/Live%20Demo-Netlify-00C7B7?style=for-the-badge&logo=netlify" alt="Live Demo">
    </a>
    <a href="https://github.com/OrangeChen011/VisionOSSimu-html/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/OrangeChen011/VisionOSSimu-html?style=for-the-badge" alt="License">
    </a>
    <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20VR-8A2BE2?style=for-the-badge" alt="Platform">
  </p>
  <br>
  <img src="https://via.placeholder.com/800x400?text=VisionOS+Simulator+Screenshot" alt="项目截图" width="80%" style="border-radius: 20px; box-shadow: 0 10px 40px rgba(0,0,0,0.3);">
</div>

---

## ✨ 核心特性

| 🧠 智能交互 | 🎨 视觉风格 | 📱 多端适配 |
|-------------|-------------|-------------|
| **眼动追踪** – 注视图标高亮动画 | **毛玻璃 UI** – 真实相机穿透背景 | **响应式布局** – 手机/平板/桌面均完美 |
| **手部捏合** – 隔空打开应用 | **多张壁纸** – 海滩/山脉/美式卧室 | **陀螺仪联动** – 倾斜设备图标 3D 旋转 |
| **点击无感启动** – 无需按钮，自然交互 | **圆形缩略图面板** – 点击山图标优雅切换 | **免费部署** – 一键发布到 Netlify |

---

## 🚀 在线体验

👉 **立即试玩**：[Live Demo on Netlify](https://visionosdemo.netlify.app)

> 首次打开请**点击屏幕任意位置**以启动摄像头（浏览器安全要求），然后允许摄像头权限即可开启眼动和手部追踪。

---

## 🛠️ 本地运行

1. **克隆仓库**
   ```bash
   git clone https://github.com/OrangeChen011/VisionOSSimu-html.git
   2.进入目录
   cd VisionOSSimu-html
   3.启动本地服务器（摄像头 API 要求 localhost 或 HTTPS）
# 使用 Python 3
python -m http.server 8000
# 或使用 Node.js
npx serve .
4.浏览器访问http://localhost:8000
