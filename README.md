# Digital_Trust_Shield_
# 🛡️ Digital Trust Shield v2.0

> **AI-Powered Misinformation Detection & Digital Forensics Platform**

A fully client-side cybersecurity web application for detecting fake news, analyzing image forensics, and identifying AI-generated video content — built with pure HTML, CSS, and JavaScript.

![Version](https://img.shields.io/badge/version-2.0.0-00e5ff?style=flat-square)
![Status](https://img.shields.io/badge/status-active-00ff88?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-bf5fff?style=flat-square)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-ff8800?style=flat-square)

---

## 🌐 Live Demo

> Hosted on GitHub Pages:  
> **`https://YOUR-USERNAME.github.io/digital-trust-shield`**

---

## 📸 Preview

| Hero Section | Image Forensics Lab | AI Video Detector |
|---|---|---|
| Cyberpunk dark theme with animated matrix rain | ELA analysis + anomaly heatmap overlay | Frame-by-frame AI detection + confidence donut |

---

## ✨ Features

### 🔗 URL Verifier
- Paste any article URL or content for instant verification
- Three verdict types: **Trusted** (green) / **Suspicious** (yellow) / **Fake** (red)
- Animated step-by-step scanning process
- Trust score out of 100 with source grade, domain age, and corroborating sources
- Color-coded result tags with fact-checker attribution

### 🔬 Image Forensics Lab
- Drag & drop or click-to-upload image analysis (JPG, PNG, WEBP, BMP, TIFF)
- **Error Level Analysis (ELA)** — 3-panel view: Original, ELA Map, Anomaly Highlights
- **Heatmap overlay** drawn directly over the uploaded image showing suspicious regions
- Animated forensic metric bars:
  - AI Generation Probability
  - ELA Anomaly Level
  - Noise Pattern Consistency
  - Clone/Copy Detection
  - Metadata Integrity
  - JPEG Compression Artifacts
- 6 selectable analysis modules (ELA, Metadata, AI Generation, Clone Detection, Noise, Steganography)
- Dynamic verdict badge: LIKELY AUTHENTIC / SUSPICIOUS / AI GENERATED

### 🎬 AI Video Detector
- Drag & drop video upload with live playback (MP4, MOV, AVI, WEBM)
- **Facial detection overlay** — bounding boxes with REAL/DEEPFAKE labels and confidence %
- **Audio waveform visualization** with anomaly segments highlighted in red
- **Animated donut confidence chart** showing AI probability score
- **Frame-by-frame analysis strip** — 12 thumbnails each labeled REAL / SUS / FAKE
- Detection metric bars: facial deviation, blinking naturalness, skin coherence, background consistency
- Signal grid: Facial Coherence, Audio-Video Sync, GAN Fingerprint, Temporal Stability
- 6 toggleable detection modules

---

## 🎨 Design

- **Dark cyberpunk theme** — deep navy/black backgrounds
- **Animated matrix rain** — falling characters background (Japanese + binary)
- **Neon accents** — green (`#00ff88`), cyan (`#00e5ff`), purple (`#bf5fff`)
- **Glassmorphism cards** — backdrop blur with transparent borders
- **CRT scanline overlay** — authentic terminal aesthetic
- **Orbitron + Rajdhani + Share Tech Mono** font stack
- **Smooth scroll animations** — fade-in on intersection observer
- **Animated stat counters** — numbers count up on scroll
- Fully **responsive** — mobile and desktop

---

## 🚀 Getting Started

### Option 1: Just open the file
```bash
# No installation needed — it's a single HTML file
open index.html
```

### Option 2: Serve locally
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

### Option 3: GitHub Pages
1. Fork or upload this repo
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Visit `https://YOUR-USERNAME.github.io/digital-trust-shield`

---

## 📁 Project Structure

```
digital-trust-shield/
│
├── index.html          # Main application (single-file)
└── README.md           # This file
```

> Everything is contained in a single `index.html` file — no dependencies, no build step, no npm install.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and canvas elements |
| CSS3 | Glassmorphism, animations, matrix effects |
| Vanilla JavaScript | All forensic logic, canvas rendering, UI |
| Canvas API | ELA maps, heatmaps, waveform, donut chart, frame thumbnails |
| Google Fonts | Orbitron, Rajdhani, Share Tech Mono |
| IntersectionObserver | Scroll-triggered animations |

**Zero external dependencies. No frameworks. No build tools.**

---

## 📋 Modules Breakdown

### Image Forensics Engine (Simulated)
```
Upload Image → Preview + ELA Analysis → Heatmap Overlay → Metric Bars → Verdict
```
- ELA (Error Level Analysis) simulates JPEG recompression artifact detection
- Heatmap uses radial gradients to highlight region-level anomalies
- Metric scoring is randomized for demonstration purposes

### Video AI Detection Engine (Simulated)
```
Upload Video → Playback → Scan Overlay → Frame Strip → Donut Chart → Signal Grid
```
- Facial bounding boxes simulate landmark detection output
- Waveform canvas renders audio anomaly visualization
- Frame strip simulates per-frame AI classifier output
- Donut arc chart shows overall AI probability

> ⚠️ **Note:** All analysis in this demo is **simulated/educational**. Real forensic accuracy requires server-side ML models (e.g., FaceForensics++, CNNDetection, MediaPipe).

---

## 🔮 Roadmap

- [ ] Connect to real AI APIs (Hive Moderation, Google SafeSearch)
- [ ] Real ELA via server-side Python (PIL/Pillow)
- [ ] FaceForensics++ deepfake model integration
- [ ] Browser extension version
- [ ] REST API backend (FastAPI / Node.js)
- [ ] User history & saved scans
- [ ] Multi-language support

---

## 🤝 Contributing

Contributions welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/real-ela-analysis`)
3. Commit your changes (`git commit -m 'Add real ELA via canvas API'`)
4. Push to the branch (`git push origin feature/real-ela-analysis`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## ⚠️ Disclaimer

This tool is built for **educational and demonstration purposes only**. The forensic analysis shown is simulated to illustrate how real AI-powered detection systems work. It should not be used as the sole basis for determining the authenticity of any media or news content.

---

## 👨‍💻 Author

Built with ❤️ using [Claude](https://claude.ai) by Anthropic.

---

*Fighting misinformation, one scan at a time.* 🛡️
