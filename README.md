# 🧠 NEURO-FRIED: FINAL SURVIVAL

> **"Time is the only currency. And yours is bleeding out."**

A **horror-themed survival trivia game** where time is your health. Built with pure vanilla HTML/CSS/JavaScript. No frameworks. No mercy.

![NEURO-FRIED](https://img.shields.io/badge/NEURO--FRIED-FINAL%20SURVIVAL-ff3300?style=for-the-badge)
![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-yellow?style=flat-square)
![Single File](https://img.shields.io/badge/Single-HTML%20File-green?style=flat-square)
![Game Jam](https://img.shields.io/badge/Codédex-Game%20Jam%202025-purple?style=flat-square)

---

## 🎮 PLAY NOW

🔗 **[Play Live](https://neuro-fried.vercel.app)**  
📹 **[Video Summary](https://youtu.be/2fnb_pqz9tg?si=mQmNC4BfxeFqS-Om)**  
🏆 **[Codédex Submission](https://www.codedex.io/community/monthly-challenge/submission/ey67zVFIYoP3H2AcAeWK)**

---

## 🕹️ CONTROLS

| Key | Action |
|-----|--------|
| **Click** | Select answers |
| **SPACE** | Freeze time (5 seconds) |
| **R** | Rewind (recover time) |
| **Drag** | Move any UI element |
| **Double-tap** | Start game |

---

## 🎯 GAME MODES

### 1. 🎲 OWN LUCK (Standard Survival)
- Classic trivia with time pressure
- **+5s** correct / **-5s** wrong
- Boss Nodes every 5th question (2x timer speed)
- Build combo multipliers for massive scores

### 2. 🌀 TIME LOOP (Roguelike)
- Death loops you back with **50% score penalty**
- **Timeline Corruption** tracks damage across deaths
- Multiple endings based on corruption level
- Loop counter shows how many times you've failed

### 3. ⚔️ PARADOX (Inverted Reality)
- **Sanity Meter** replaces timer
- When screen glitches, pick the **WRONG** answer
- Reality inverts randomly—stay alert
- Pure mental warfare

---

## ⏰ THEME: "THE CHANGING OF TIME"

| Feature | Implementation |
|---------|----------------|
| **Timer = Health** | Every second you lose brings death closer |
| **Freeze Power** | Halt temporal decay for 5 seconds |
| **Rewind Power** | Undo mistakes, recover lost time |
| **Boss Nodes** | Time accelerates 2x every 5th question |
| **Time Loop Mode** | Death → corruption → different endings |
| **Chrono Acceleration** | Difficulty scales the longer you survive |

---

## 🔥 FEATURES

### Gameplay
- **400+ questions** across 16 categories (Gaming, AI, Crypto, Space, Physics, etc.)
- **16 achievements** with popup notifications
- **Identity Registration** with photo upload for personalized game cards
- **Fate Wheel** spin determines your luck modifier
- **Draggable HUD** — reposition timer, score, buttons anywhere

### Visual Effects
- **Parallax tilt system** responds to game state
- **Particle explosions** on correct answers
- **Horror aesthetic**: blood veins, glitches, scanlines, vignette
- **Cinematic video backgrounds** on every screen
- **Screen shake & chromatic aberration** on wrong answers

### Audio
- **Multi-track BGM** with crossfade transitions
- **Procedural typing sounds** generated in real-time
- **Dynamic audio ducking** for SFX clarity

### Technical
- **Single HTML file** (~14,000 lines)
- **Zero external image assets** for UI (pure CSS/Canvas)
- **Custom cursor & scrollbar** styling
- **Responsive design** for desktop

---

## 📁 FILE STRUCTURE

```
/neuro-fried
├── index.html              # THE ENTIRE GAME
├── README.md               # This file
├── landing bgm.mp3         # Landing page music
├── gamestart bgm.mp3       # Menu/intro music
├── gameplay bgm.mp3        # Main gameplay music
├── gameover bgm.mp3        # Death screen music
├── assets/
│   ├── vid/                # Video backgrounds (cine.mp4, hud1.mp4, etc.)
│   ├── *.png               # Tutorial/preview images
│   ├── freeze.mp4          # Power demo videos
│   └── rewind.mp4
└── fonts/                  # Custom typography
    ├── LigerRegular.ttf
    ├── BlackgothRegular.otf
    ├── FastlaneThree.ttf
    └── ...
```

---

## 🚀 HOW TO PLAY

### 🌐 Play Online (Recommended)
**👉 [neuro-fried.vercel.app](https://neuro-fried.vercel.app)**

Just click and play. No installation required.

### 💻 Run Locally
```bash
git clone https://github.com/Kaustavoffx/neuro-fried.git
cd neuro-fried
# Open index.html in any browser
```

> 🎧 **Recommended:** Use headphones for full horror experience

---

## 🛠️ TECH STACK

| Technology | Usage |
|------------|-------|
| **HTML5** | Structure |
| **CSS3** | ALL visual effects (animations, glass, glitch, blood) |
| **Vanilla JavaScript** | Game logic, no frameworks |
| **Canvas API** | Particle system (1000+ particles) |
| **Web Audio API** | Procedural sound synthesis |
| **html2canvas** | Screenshot capture (only external lib) |

---

## 🏆 ACHIEVEMENTS

16 unlockable achievements including:
- 🩸 First Blood — Answer your first question
- 🔥 Hot Streak — 5 correct in a row
- ⏰ Time Lord — Use Freeze power
- ⏪ Temporal Paradox — Use Rewind power
- 🎓 Perfect Mind — Complete game with zero mistakes
- ⭐ Timeline Purist — Win without using any powers
- 🤫 *Secret* — Click the title 10 times...

---

## 📊 QUESTION CATEGORIES

| Category | Icon |
|----------|------|
| Gaming History | 🎮 |
| AI Revolution | 🧠 |
| Crypto & Web3 | ⛓️ |
| Space Exploration | 🚀 |
| Physics | ⚛️ |
| VR & AR | 🥽 |
| Tech Founders | 👔 |
| Biotech & Future | 🧬 |
| Energy & Auto | ⚡ |
| Operating Systems | 💻 |
| Social Media | 📱 |
| Tech Startups | 💼 |
| Finance | 💰 |
| General Facts | 📚 |
| + more... | |

---

## 🎨 DESIGN PHILOSOPHY

> **"90% of dev time spent on JUICE"**

Every interaction has feedback:
- Buttons glow and pulse
- Particles explode on success
- Screen shakes on failure
- Colors shift with game state
- Typography animates constantly

**No placeholders. Everything polished. Pure game feel.**

---

## 📜 CREDITS & LINKS

**Design, Code & Obsessive Polish:** Kaustav Chowdhury

| Platform | Link |
|----------|------|
| 🎮 **Play Game** | [neuro-fried.vercel.app](https://neuro-fried.vercel.app) |
| 📹 **Video Summary** | [YouTube](https://youtu.be/2fnb_pqz9tg?si=mQmNC4BfxeFqS-Om) |
| 🏆 **Codédex Submission** | [View Entry](https://www.codedex.io/community/monthly-challenge/submission/ey67zVFIYoP3H2AcAeWK) |
| 💼 **LinkedIn** | [Kaustav Chowdhury](https://www.linkedin.com/in/kaustav-chowdhury-771164397) |
| 🐙 **GitHub** | [Kaustavoffx](https://github.com/Kaustavoffx) |

Made with ❤️ and dangerous amounts of caffeine.

---

## 📄 LICENSE

This project was created for the **Codédex December 2025 Game Jam**.

Theme: *"The Changing of Time"*

---

*System Monitor: ONLINE*  
*Signal Strength: 100%*  
*...Entity Watching...*

**🩸 TIME IS BLEEDING. WILL YOU SURVIVE? 🩸**
