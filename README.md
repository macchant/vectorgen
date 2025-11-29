# VectorGen // SYSTEM_V6

[![Live Demo](https://img.shields.io/badge/DEMO-VISIT%20SITE-22d3ee?style=for-the-badge&logo=vercel&logoColor=white)](https://vectorgen-sepia.vercel.app/)

![Version](https://img.shields.io/badge/version-v6.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

**VectorGen** is a professional-grade AI prompt architect...

It features a **Sci-Fi Tactical UI** inspired by Sci-Fi Tactical game, providing a visually immersive experience while generating optimized prompts for Midjourney, Ideogram, Leonardo, and Flux.

---

## ⚡ Core Modules

### 1. Multi-Model Syntax Engine
The system automatically reformats your prompt based on the selected AI model:
* **Midjourney V6:** Injects `--ar`, `--s`, and `--no` parameters (shading/3d/photo) automatically.
* **Ideogram:** Activates "Typography Mode" to handle text rendering perfectly.
* **Leonardo.ai:** Removes syntactic flags and optimizes for natural language.
* **Flux/Whisk:** Uses high-fidelity dense descriptors.

### 2. Specialized Composition Modes
* **Single Isolation:** Adds "die-cut," "white background," and "centered" keywords for easy background removal.
* **Knolling Grid (Sticker Sheet):** Forces the AI to generate a "Sprite Sheet" or "Knolling Layout," perfect for creating sticker packs or icon sets.

### 3. Visual Tag Selector
No need to memorize keywords. Select from pre-configured professional tags:
* **Styles:** Flat Vector, Corporate Memphis, Bauhaus, Pop Art, Kawaii, etc.
* **Linework:** Monoline, Thick Outlines, Stippling, Halftone Dots, etc.

---

## 🚀 Deployment / Installation

Since VectorGen is a **Single-File Application**, no installation or server is required.

### Method A: Run Locally
1.  Download the `index.html` file.
2.  Double-click to open it in Chrome, Edge, or Safari.
3.  **System Ready.**

### Method B: Host on GitHub Pages (Recommended)
1.  Fork or Clone this repository.
2.  Go to **Settings** > **Pages**.
3.  Select `main` branch as source.
4.  Your app will be live at `https://macchant.github.io/VectorGen`.

---

## 🛠️ Tech Stack

* **Core:** HTML5 / Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **Typography:** 'Outfit' & 'JetBrains Mono' (Google Fonts)
* **Icons:** Phosphor Icons
* **Architecture:** Zero-Dependency, Client-Side Only (No API Keys required).

---

## 🤝 Contributing

This project is open source. If you want to add new Art Styles or features:
1.  Fork the repository.
2.  Edit the `data` object in the script section of `index.html`.
3.  Submit a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <sub>Built with 💠 by [macchant]</sub>
</div>
