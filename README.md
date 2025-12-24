# 👻 Ghost-Pixel | Anti-AI Image Cloak

> **"Visible to humans. Invisible to machines."**

![Status](https://img.shields.io/badge/Status-Operational-brightgreen)
![Privacy](https://img.shields.io/badge/Privacy-Client--Side-blueviolet)
![License](https://img.shields.io/badge/License-MIT-orange)

**Ghost-Pixel** is a browser-based privacy tool designed to protect your digital identity from unauthorized facial recognition and AI surveillance. By utilizing **Adversarial Perturbation** algorithms, it modifies image pixels at a microscopic level—confusing neural networks without altering the visual aesthetics for human viewers.

## 🛡️ The Philosophy

In an era of mass surveillance, your face is your data. Ghost-Pixel empowers users to reclaim ownership of their likeness. It creates a "mathematical veil" over your photos, making them useless for data scraping bots and recognition models.

## ✨ Key Features

* **Adversarial Noise Injection:** Adds imperceptible pixel-level noise that disrupts AI pattern matching.
* **100% Client-Side:** No server uploads. All processing happens locally in your browser using the HTML5 Canvas API. Your photos never leave your device.
* **Metadata Scrubber:** Automatically strips EXIF data (GPS, Device Model, Timestamp) during processing.
* **Adjustable Intensity:** Slider control to balance between invisibility (noise level) and image clarity.
* **Glitch Mode:** Optional visual distortion for aesthetic privacy.

## 🚀 How to Use

1.  **Upload:** Drag & drop your image (JPG/PNG).
2.  **Configure:** Adjust the **Noise Intensity** slider.
    * *Low (1-10%):* Best for social media (hard to detect noise).
    * *High (20%+):* Maximum security against advanced AI models.
3.  **Process:** Click **"Execute Cloak"**. The system will inject the noise matrix.
4.  **Download:** Save your secured image.

## 🛠️ Tech Stack

* **Core:** Vanilla JavaScript (ES6+)
* **Graphics:** HTML5 Canvas API (`getImageData`, `putImageData`)
* **Styling:** CSS3 (Cyberpunk/Stealth Aesthetic)

## ⚠️ Disclaimer

This tool is a **Proof of Concept** for privacy research. While effective against many standard recognition models, no digital defense is absolute. Use it as a layer of protection, not a guarantee.

---
<div align="center">
  <p>Designed & Developed by <a href="https://github.com/syntaxandsoz"><b>Syntax & Soz</b></a></p>
  <p><i>"Reclaim your pixels."</i></p>
</div>
