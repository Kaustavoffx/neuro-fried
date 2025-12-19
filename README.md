# 🧠 NEURO-FRIED: SIGNAL LOST

> *"Time is the only currency. Spend it wisely."*

**Neuro-Fried** is a high-octane, horror-themed trivia survival game built entirely within a single HTML file. It combines intense resource management, psychological horror elements, and rapid-fire questions to test your knowledge under pressure.

## 🕹️ Game Overview

The objective is simple: **Survive the Timeline.**
Answer questions correctly to maintain your signal integrity. Fail, and face the void.

### 🎮 Game Modes

1.  **🎯 OWN LUCK (Standard Mode)**
    *   Classic survival trivia.
    *   Utilize **Time Powers** (Freeze, Rewind) to manipulate the clock.
    *   Manage your score multiplier to maximize your "Aura".

2.  **🌀 TIME LOOP (Dream Mode)**
    *   Death is not the escape.
    *   Features random "Dream Sequences" that distort reality.
    *   If you fail, you loop back with a penalty, trapped until you stabilize the timeline.

3.  **⚔️ PARADOX MODE (PvE)**

        *   **Sanity Meter** replaces Health.
        *   **Wrong answers** damage your Sanity.
        *   **LOGIC INVERSION:** If text glitches, pick the **WRONG** answer.
        *   **Chaos Level** rises over time.
        *   **Objective:** Survive against your own mind.

## 🛠️ Technical Features

*   **Single-File Architecture**: The entire game engine, logic, CSS, and HTML structure lives in `index.html`. No build steps required.
*   **Neuro-Audio System**:
    *   Adaptive BGM switching (Start → Gameplay → Game Over).
    *   Smart volume ducking during interactions.
    *   Horror SFX integration.
*   **Visual Engine**:
    *   **Canvas Particles**: Interactive background reacting to game state (calm vs. rewind).
    *   **CSS3 Advanced Animations**: CRT scanlines, chromatic aberration, and glitch effects.
    *   **Black Hole Implosion**: A custom exit transition that physically distorts the DOM elements into a singularity.
*   **Responsive Design**: Fully playable on Desktop and Mobile devices.

## 📂 Project Structure

```text
/game-jam-entry
├── index.html          # THE CORE: Game Engine, UI, and Logic
├── README.md           # This file
├── bgm.mp3             # Legacy Audio
├── gamestart bgm.mp3   # Intro Ambience
├── gameplay bgm.mp3    # High-Tension Loop
└── gameover bgm.mp3    # "Signal Lost" Theme
```

## 🚀 How to Run

1.  Clone the repository.
2.  Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox).
3.  **Recommendation**: Use Headphones for the intended 3D audio horror experience.

## 🎨 Credits & Assets

*   **Design & Code**: Kaustav Chowdhury
*   **Audio Assets**:
    *   `gamestart bgm.mp3`
    *   `gameplay bgm.mp3`
    *   `gameover bgm.mp3`
    *   *(Audio engine handles seamless transitions between these tracks)*
*   **Fonts**:
    *   *Orbitron* (Titles)
    *   *Rajdhani* (UI)
    *   *VT323* (Terminal/Data)

---
*System Monitor: ONLINE*
*Signal Strength: 100%*
*...Entity Watching...*
