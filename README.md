# 🖥️ Terminalizer
### A retro-style CRT terminal that transforms any uploaded image into blue phosphor pixel art.

link: https://triloux.github.io/terminalizer/

Terminalizer recreates the aesthetic of the retro office computers.
Your uploaded image is displayed inside a vintage CRT monitor frame and rendered into **multi‑shade blue phosphor pixels**, complete with:

- Pixel‑size control  
- User‑defined number of shades (2–6)  
- Completely client‑side processing  
- Works offline  
- Downloadable output

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| **Blue phosphor CRT look** | Shades quantized from deep navy → cyan glow |
| **Variable pixel size** | Chunky or fine pixelation |
| **Shades slider (2–6)** | Posterized multi‑tone look |
| **No server uploads** | All processing happens in your browser |
| **Download as PNG** | Saves just the rendered screen |

---

## 🧩 How it Works

The image is downscaled to a pixel grid, luminance is calculated per pixel, and mapped to **N shades** along a blue gradient:

- Darkest → `#001533`
- Midtones → interpolated values
- Brightest → `#66CCFF`

This produces the signature Severance monochrome‑terminal vibe.

---

## 📁 Using Locally

Clone or download the repo:

Open:

```
index.html
```

That’s it. No build tools, no dependencies.

---

## 🧱 Tech Stack

- HTML5 Canvas (pixel manipulation)
- Vanilla JavaScript  
- Pure CSS for monitor frame and glow layers
- No frameworks

---

## 📦 Project Structure

```
/
├── index.html       # Entire app in one file
├── README.md
└── assets/          # (optional future expansion)
```

---

## 📝 License

MIT License — free to use, modify, and ship.

---

## ⭐ Like this project?

Consider starring the repo so more people can find it!
