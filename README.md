# 🪄 ChromaErase Pro - AI & In-Browser Background Removal Tool

**ChromaErase Pro** is a modern, high-performance web application designed for fast, privacy-focused image background removal and replacement. It features an in-browser HTML5 Canvas color-keying processing engine alongside cloud-based AI processing via the Remove.bg API.

---

## ✨ Features

- ⚡ **Dual Processing Engines**:
  - **In-Browser Client Canvas Engine**: Works 100% locally and offline without sending images to external servers. Features Euclidean color-distance keying, edge smoothing, and adjustable background sensitivity threshold.
  - **Cloud AI Engine**: Optional integration with Remove.bg API for complex portrait matting.
- 🎨 **Background Replacement Suite**:
  - **Transparent Checkerboard**: High-precision PNG export with transparent backgrounds.
  - **Solid Color Swatches**: Pure white, dark slate, studio gray, or custom HTML5 color picker.
  - **Vibrant Gradients**: Pre-set CSS linear gradients (Neon Pulse, Emerald Wave, Sunset Glow).
  - **Custom Image Upload**: Use any custom picture as the background behind the extracted subject.
- 🪟 **Interactive Split View Comparison**:
  - Real-time side-by-side Before/After slider to inspect mask accuracy and edge quality.
- 📷 **Instant Demo Samples**:
  - Built-in SVG samples (Portrait, Product, Vehicle) to test features immediately without uploading personal files.
- 📱 **Modern Glassmorphic UI**:
  - Dark mode aesthetic with responsive layout for desktop, tablet, and mobile devices.

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla JavaScript (ES6+), CSS3 (Flexbox & Grid, CSS Custom Properties).
- **Core Engine**: HTML5 Canvas API (ImageData, Color Keying, Feathering).
- **Icons & Fonts**: FontAwesome 6, Google Fonts (*Plus Jakarta Sans*, *Inter*).
- **Hosting / Deployment**: Compatible with GitHub Pages, Vercel, Netlify, or any static HTTP web server.

---

## 🚀 Getting Started

### Local Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Omkar4812x/Background-Removal-Tool.git
   ```
2. Navigate into the directory:
   ```bash
   cd Background-Removal-Tool
   ```
3. Open `index.html` directly in any standard browser (Chrome, Edge, Firefox, Safari) or use a local static server like `npx serve` or Live Server.

---

## 📖 Usage Guide

1. **Upload an Image**: Drag & drop any image file (PNG, JPG, WEBP) into the dropzone or click **Browse File**.
2. **Select Engine**: Choose **Client Canvas** for instant offline removal or **Remove.bg API** for cloud AI removal.
3. **Adjust Controls**:
   - Tweak **Background Sensitivity** to fine-tune background removal tolerance.
   - Adjust **Edge Smoothness** to soften borders around subjects.
4. **Choose Background**: Select Transparent, Solid Color, Gradient, or upload a Custom Background Image.
5. **Compare & Export**: Use **Split View** to inspect details, then click **Export Image (PNG)** to download the final result.

---

## 📄 License & Attribution

Created and maintained as part of the Web Applications Collection.  
Released under the MIT License.
