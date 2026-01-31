# Zenly SlideClean - Premium AI Watermark Remover

[![Hosted on GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://slides.zenlytool.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Local-green?style=for-the-badge)](https://slides.zenlytool.com/)

> **🧹 Professional, private, and offline watermark remover for NotebookLM slides and images.**

Zenly SlideClean is engineered to provide a seamless, high-precision cleaning experience for presentation slides, specifically optimized for Google's NotebookLM exports.

---

## ✨ Features

- **🚀 Instant Cleaning:** Zero-latency removal using optimized pixel-cloning.
- **🔒 Privacy Native:** 100% client-side. Your files never leave your browser.
- **💎 Lossless Quality:** Only watermarks are removed; your slide content remains at original resolution.
- **📱 PWA Ready:** Install it as a standalone app on your desktop or mobile device.
- **🌊 Premium UI:** Modern, glassy aesthetics with smooth reveal animations.

---

## 🛠️ How It Works

SlideClean uses a sophisticated **Local Pixel Interpolation** engine. Instead of "blurring" the watermark, our algorithm:
1. Detects the precise coordinates of the watermark pattern.
2. Clones surrounding pixels from the slide background.
3. Patches the area with 100% color matching.
4. Re-compresses the file locally for a clean download.

---

## 🚀 Live Demo

Access the tool instantly at:  
👉 **[slides.zenlytool.com](https://slides.zenlytool.com/)**

---

## 📂 Project Structure

- `index.html` - Main application logic and UI
- `assets/` - Icons, localized libraries, and fonts
- `manifest.json` - PWA configuration
- `robots.txt` & `sitemap.xml` - SEO configuration
- `llm.txt` & `llms-full.txt` - AI/LLM context files (GEO)

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Generated with ❤️ by <b>ZenlyTool</b>
</p>
