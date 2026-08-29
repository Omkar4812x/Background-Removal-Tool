# 🪄 ChromaErase Pro v2.0 - AI & In-Browser Background Removal Studio

**ChromaErase Pro v2.0** is an open-source, ultra-fast background removal and photo editing studio. It combines automatic canvas color-keying, cloud AI background removal, manual touch-up brushes (Erase & Restore), a subject drop shadow generator, image filters, and multi-scale HD export into a single 100% in-browser web application.

---

## ✨ Key Features in v2.0 Pro

- ⚡ **Dual Engine Background Removal**:
  - **Client Canvas Engine**: 100% local, offline Euclidean color-distance keying algorithm with adjustable sensitivity threshold.
  - **Cloud AI Engine**: Integration with Remove.bg API for complex portrait matting.
- 🖌️ **Manual Touch-Up Tools**:
  - **Erase Brush**: Manually remove unwanted background spots or stray edges.
  - **Restore Brush**: Bring back accidentally erased subject details.
  - Adjustable **Brush Size** (5px–120px) and **Brush Hardness/Softness** with a live ring indicator.
- ☀️ **Subject Drop Shadow Generator**:
  - Add realistic drop shadows with custom blur radius, X/Y offsets, shadow color picker, and opacity controls.
- 🎛️ **Image Adjustments & Filters**:
  - Fine-tune extracted subject brightness, contrast, and color saturation.
- 🔄 **Canvas Flip & Transform**:
  - Instant Flip Horizontal and Flip Vertical controls.
- ⏪ **Undo / Redo History Stack**:
  - Full edit history stack (`Ctrl+Z` / `Ctrl+Y`) for all brush strokes and mask adjustments.
- 📋 **Advanced HD Export & Copy to Clipboard**:
  - Export formats: **PNG** (lossless transparent), **JPEG**, **WEBP**.
  - Resolution scaling: **1x Original**, **2x HD**, **4x 4K Resolution**.
  - **1-Click Copy to Clipboard**: Copy transparent PNG directly to system clipboard for instant pasting into Canva, Photoshop, or messaging apps.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `E` | Switch to **Manual Erase Brush** |
| `B` | Switch to **Manual Restore Brush** |
| `M` | Switch to **Auto Mode / View Pointer** |
| `Ctrl + Z` | **Undo** last action |
| `Ctrl + Y` | **Redo** action |
| `Ctrl + C` | **Copy Image to Clipboard** |

---

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla JavaScript (ES6+), CSS3 (Custom Variables, Flexbox, Grid).
- **Engine**: HTML5 2D Canvas API (ImageData manipulation, radial gradient mask drawing, shadow filters).
- **Design System**: Dark glassmorphic aesthetic, FontAwesome 6, Google Fonts (*Plus Jakarta Sans*, *Inter*).

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Omkar4812x/Background-Removal-Tool.git

# Navigate to the folder
cd Background-Removal-Tool

# Open index.html in any modern browser
```

---

## 📄 License

Maintained as part of the Web Applications collection under the MIT License.
