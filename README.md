# 🪢 Raksha Bandhan — Interactive 3D Celebration Experience

An interactive 3D web celebration tribute designed to showcase creative front-end engineering, WebGL rendering with Three.js, procedural particle systems, and polished UI micro-interactions.

> **Portfolio Demo Edition:** This repository contains a public-safe version configured with curated royalty-free demonstration imagery and a clean Git history.

---

## ✨ Features

- **3D Rakhi & Locket Experience (Three.js):**
  - Custom 3D procedural Rakhi model featuring gold thread, pearl beads, faceted ruby gemstone, and golden concentric rings.
  - Realistic physics drop-and-bounce entry animation.
  - Interactive mouse-tracking tilt and 3D rotation.
  - Clickable center pendant that opens with a golden particle burst transition into the memory world.

- **Lock Screen & Secret PIN Gate:**
  - 3D animated padlock with shackle release and shake animations on invalid input.
  - **Demo Secret PIN:** `7` (also subtly hinted on the lock screen).
  - Ambient floating golden ember canvas background.

- **3D Coverflow Carousel:**
  - Smooth 3D card perspective transformations (`translateZ`, `rotateY`, progressive blur).
  - Full keyboard (`←` / `→`), touch swipe gesture, and hover auto-play support.
  - Seamless full-screen lightbox modal for viewing high-res moments.

- **Interactive Polaroid Wall:**
  - Randomly tilted polaroids with dynamic hover lift and shadow depth.
  - IntersectionObserver scroll reveal animations.

- **Cousin Bond Flip Cards:**
  - 3D card-flip animations revealing nostalgic and relatable sibling moments.

- **Polished UX & Theme Engine:**
  - Dark, Light, and System Theme modes with custom CSS tokens and glassmorphism.
  - Web Audio API synthesized sound effects (synthesized sine & chime tones with no audio file downloads).
  - Mobile-first, fully responsive layout tested on desktop, tablet, and mobile displays.
  - Image fallback resilience with CDN failover handling.

---

## 🛠️ Technology Stack

- **Graphics & 3D:** [Three.js (r128)](https://threejs.org/)
- **Core:** HTML5, Modern Vanilla JavaScript (ES6+)
- **Styling:** Vanilla CSS3 (Custom Properties, 3D Perspective, Glassmorphism, CSS Grid & Flexbox)
- **Audio:** Native Web Audio API (procedural oscillator synthesis)
- **Typography:** Google Fonts (*Marcellus*, *Cormorant Garamond*, *Assistant*)

---

## 🚀 Getting Started

This project is built with zero build dependencies—no complex bundle steps or node installations are required to run it locally.

### 1. Clone the repository
```bash
git clone https://github.com/arasadaanishkarthik/Rakhi4Cousins.git
cd Rakhi4Cousins
```

### 2. Run locally
You can open `index.html` directly in any modern browser, or run a local HTTP server:

**Using Python:**
```bash
python -m http.server 3000
```

**Using Node / npx:**
```bash
npx serve .
```

Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🌐 Deploying to GitHub Pages

1. Go to the repository **Settings** on GitHub.
2. Under the **Code and automation** section, click **Pages**.
3. Under **Build and deployment > Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Within 1–2 minutes, your website will be live at:
   `https://arasadaanishkarthik.github.io/Rakhi4Cousins/`

---

## 🛡️ Privacy & Image Licensing

All photographs included in this public demonstration repository are sourced under the [Unsplash License](https://unsplash.com/license) for open, royalty-free commercial and personal use. No personal family photographs or private information are included in this repository.

---

## 👤 Author

**Anish Karthik**
- GitHub: [@arasadaanishkarthik](https://github.com/arasadaanishkarthik)
