# Rangan Pratik Borah — Portfolio

Personal portfolio website for **Rangan Pratik Borah**, Electronics & Communication Engineering student at VIT Vellore.

🌐 **Live:** [resume-ranganpb.com](https://resume-ranganpb.com)

---

## Tech Stack

| Layer | Technology |
|---|---|
| UI | React 18 (CDN, no build step) |
| Styling | Tailwind CSS (CDN) |
| Animations | Framer Motion v6 |
| Transpiler | Babel Standalone |
| Hosting | Vercel |

Single-file architecture — the entire app lives in `portfolio.html`.

---

## Features

- Animated hero with full-screen video background
- Portrait photo carousel with left/right navigation
- Sticky project cards that stack on scroll with scale + z-index layering
- Skills marquee, About, and Contact sections
- Résumé download button
- Fully responsive (mobile → desktop)
- Open Graph meta tags for social sharing

---

## Projects Showcased

1. **MouFace NEXUS AI** — Real-time face recognition (Java, OpenCV, Spring Boot)
2. **Moodora AI** — Emotion-based music recommendation (React, MediaPipe, Spotify API)
3. **Aparupa AI · Smart Irrigation** — IoT irrigation with edge AI (Arduino, ESP32)
4. **Passcode-Based Electronic Security System** — Hardware security project (Embedded)
5. **Half Adder** — Digital logic design (HDL)

---

## Local Development

Requires [Node.js](https://nodejs.org) for the dev server.

```bash
npx serve -l 5500 .
```

Then open [http://localhost:5500/portfolio.html](http://localhost:5500/portfolio.html)

---

## Project Structure

```
portfolio/
├── portfolio.html          # Entire app
├── vercel.json             # Vercel routing config
├── assets/
│   ├── portrait.jpg        # Hero portrait
│   ├── logo.png            # RPB logo / favicon
│   ├── bg.mp4              # Video background
│   ├── hero_*.jpeg         # Hero carousel photos
│   ├── bg-frames/          # Fallback background frames
│   └── projects/           # Project media (images + videos)
└── Rangan_Pratik_Borah_Resume.pdf
```

---

## Contact

- **Email:** ranganpratikborah2006@gmail.com
- **LinkedIn:** [rangan-pratik-borah-69957b375](https://www.linkedin.com/in/rangan-pratik-borah-69957b375/)
- **GitHub:** [RanganBorah](https://github.com/RanganBorah)
