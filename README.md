# 🧠 NEURO-FRIED: FINAL SURVIVAL

> **"Time is the only currency. And yours is bleeding out."**

Yo! This is **NEURO-FRIED**, my submission for the jam. I didn't just want to make a trivia game; I wanted to make a **panic attack that feels like a rave**.

I spent **90% of the dev time on JUICE**.

**🔥 What Makes This Insane:**
- **Visual Overload**: Every correct answer triggers massive particle explosions and screen shake. It's not just "+10 points", it's a tactile **CRUNCH** that makes your brain go "brrr".
- **The "God-Tier" Engine**: No game engine. Minimal external dependencies. Everything you see—the effects, the UI glow, the animations—is **pure, handmade CSS and vanilla JavaScript** rendered with raw DOM power.
- **High Stakes**: There is no health bar. **Time is your health**. Every second you hesitate, you die a little. Every wrong answer? Massive time penalty. You are constantly on the edge of your seat.

---

## 🎮 GAME MODES

### 1. 🎯 **OWN LUCK (Standard Mode)**
- Classic survival trivia with relentless time pressure
- Use **Time Powers** (Freeze & Rewind) to manipulate the clock
- Build combo multipliers for massive "Aura" points
- Boss Nodes every 5th question with 2x timer speed
- Pure skill-based progression—no mercy

### 2. 🌀 **TIME LOOP (Dream Mode)**  
- Death is not an escape—you **loop back** with penalties
- **Timeline Corruption** mechanic tracks temporal damage
- Features procedural **Dream Sequences** that distort reality
- Loop counter tracks how many times you've failed
- Multiple endings based on corruption level and loop count

### 3. ⚔️ **PARADOX MODE (PvE AI Duel)**  
- Battle against an **adaptive AI opponent** in real-time
- **Sanity Meter** instead of timer—wrong answers drain your mind
- **LOGIC INVERSION**: When text glitches, pick the **WRONG** answer to survive
- **Day-to-Night Theme Transition**: Starts bright white, descends into blood-red horror
- **Chaos Level** escalates with each question
- No timer—pure mental warfare

---

## 🔧 CORE GAME COMPONENTS

### ⏰ **Time Mechanics**
- **Countdown Timer**: Your life ticking away in real-time
- **Time Gain/Loss**: +5s correct, -5s wrong
- **Visual Time Bar**: Animated progress with color-coded danger zones
- **Anxiety Triggering**: Screen effects intensify as time drops
- **Boss Mode Timer**: 2x speed during boss nodes (every 5th question)

### 🔮 **Time Powers (Limited Uses)**
**❄️ FREEZE (Spacebar)**
- Pauses the timer for 5 seconds
- **Visual Effects**: Cyan glow, grayscale filter, ice particles
- **UI Indicator**: "FROZEN" text with pulsing animation on timer panel
- **Audio**: Procedural freeze sound effect

**⏪ REWIND (R Key)**
- Regain lost time when you fail
- **Visual Effects**: Screen distortion lines, reverse-flow particles
- **Glitch Animation**: Chromatic aberration during activation
- **Counter**: Tracks total rewinds for achievements

### 📊 **Scoring System**
- Base points per correct answer
- Combo multiplier (increases with streak)
- **Achievement Integration**: 16 unlockable achievements
- **Leaderboard**: Local high score tracking
- **Statistics**: Tracks accuracy, speed, power usage

### 🎯 **Question Database**
**20+ Categories** with 15-20 questions each:
- 🎮 Gaming History
- 💰 Finance & Crypto
- 🚀 Space Exploration
- 📱 Social Media
- 💻 Operating Systems
- ⛓️ Crypto & Web3
- 🥽 VR & AR
- 🧠 AI Revolution
- 👔 Tech Founders
- ⚛️ Physics
- 💼 Tech Hustle (Startups)
- 🧬 Biotech & Future
- ⚡ Energy & Auto
- 📚 General Facts

**Question Format:**
- Year-based timeline questions
- Multiple choice (3 options)
- Dynamic theme switching per category

---

## 🎨 VISUAL EFFECTS (THE JUICE!)

### 🌌 **Procedural Canvas System**
- **Real-time Nebula**: Mathematical gradient rendering (no images)
- **Particle Engine**: 1000+ animated particles
  - Calm drift during normal gameplay
  - Explosive burst on correct answers
  - Reverse flow during rewind
- **Starfield**: Multi-layer parallax scrolling
- **Dynamic Tilt**: Background responds to game state

### 💀 **Horror Visual Theme**
**Blood Horror Aesthetic:**
- **Tilt Ambient**: Pulsing blood-red gradient overlay
- **Blood Veins Overlay**: Creepy grid pattern animation
- **Blood Drip Effect**: Subtle vertical drips from screen edges
- **CRT Scanlines**: Retro terminal aesthetic
- **Vignette**: Dramatic edge darkening

**Screen Effects:**
- **Horror Shake**: Triggered by wrong answers
- **Glitch Screen**: Chromatic aberration and skew
- **Anxiety Pulse**: Intensifying red glow as time drops
- **Screen Distortion**: Physics-based warp effects

### ✨ **UI Polish**
**Glassmorphism:**
- Frosted glass panels with backdrop blur
- Semi-transparent backgrounds
- Blood-red border glow

**Text Effects:**
- **Royal Text Shader**: Animated gold gradient
- **Chrome Text**: Metallic silver shine
- **Glitch Title**: Chromatic aberration layers
- **Typewriter Effect**: Character-by-character reveal with blinking cursor

**Button Effects:**
- **Button Glint**: Animated light sweep
- **Pulse Animations**: Freeze/Rewind buttons breathe
- **Hover Transforms**: Scale and glow on interaction
- **Tech Clip-Path**: Asymmetrical sci-fi button shapes

### 🎭 **Transition Effects**
- **Fade from Darkness**: Cinematic black fades
- **Screen Warp**: DOM element singularity distortion
- **Mode Transitions**: Smooth opacity crossfades
- **Category Theme Swaps**: Color palette animations

---

## 🔊 AUDIO SYSTEM

### 🎵 **Multi-Track BGM Engine**
**3 Dynamic Tracks:**
- `gamestart bgm.mp3` - Ambient intro for menus
- `gameplay bgm.mp3` - High-tension loop during gameplay  
- `gameover bgm.mp3` - "Signal Lost" death theme

**Features:**
- **Seamless Transitions**: Cross-fade between tracks
- **Smart Volume Ducking**: SFX don't clash with music
- **Auto-resume**: Handles browser autoplay restrictions
- **Loop Management**: Perfect gapless loops

### 🎧 **Procedural Sound Effects**
- Typing sounds (organic keyboard synthesis)
- UI click feedback
- Power-up activation cues
- Success/fail chimes
- Horror ambience

### 🔇 **Audio Controls**
- Sound toggle button (persistent mute state)
- Visual sound on/off indicator
- Headphone warning on start screen
- Local storage saves preference

---

## 🎛️ CUSTOMIZATION & SETTINGS

### 🌈 **Theme System**
**Available Themes:**
- Horror (Default) - Blood red and violet
- Dark Monochrome - Black/ash/white only
- Finance - Gold and green
- Code - Matrix green
- Space - Purple and magenta
- Social - Pink and yellow
- Gaming - Orange and yellow
- Day/Night (Paradox Mode) - White to dark red

**Theme Toggle:**
- Dedicated theme button in header
- Smooth color transitions
- Persistent across sessions

### ⚙️ **Performance Options**

**Graphics Toggle (⚡/✨):**
- High: Full effects with backdrop blur
- Low: Disables blur, blood effects, and scanlines

**Safe Mode (👁️/🛡️):**
- Reduces motion for accessibility
- Disables screen shake and glitch animations
- Prevents motion sickness

### 📱 **Responsive Design**
- Desktop-optimized with keyboard shortcuts
- Mobile touch support
- Adaptive button sizing
- Responsive modal scaling

---

## 🏆 ACHIEVEMENT SYSTEM

**16 Unlockable Achievements:**
- 🩸 First Blood - Answer first question
- 🔥 Hot Streak - 5 correct in a row
- ⚡ Unstoppable - 10 correct streak
- 🚀 Warp Speed - Reach 2x multiplier
- ⏰ Time Lord - Use Freeze power
- ⏪ Temporal Paradox - Use Rewind
- 🎯 Chrono Master - Use both powers
- 🧠 Neural Sync - Complete a game
- 🏃 Speed Demon - Win with 30s+ remaining
- 💀 Survivor - Win with <5s remaining
- 🎓 Perfect Mind - Win with zero mistakes
- 🎲 Risk Taker - Use Rewind 3+ times
- 👑 Comeback King - Drop below 10s and survive
- ⭐ Timeline Purist - Win without using powers
- 🧊 Ice Breaker - Win without Freeze
- 🚫 No Looking Back - Win without Rewind

**Features:**
- Popup notifications with animations
- Achievement gallery modal
- Progress tracking (X/16 unlocked)
- Persistent local storage

---

## 📺 GAME SCREENS & UI

### **Title Screen**
- "NEURO FRIED" glitch title with chromatic aberration
- Floating animation
- Mission log with glassmorphism
- "Initialize System" royal button
- Toggle controls (Sound, Theme)

### **Mode Selection**
- Three game mode cards
- Rules overlay with violet styling
- Mode-specific descriptions
- Visual theme previews

### **Gameplay Screen**
**HUD Elements:**
- Timer panel (top-left, draggable)
- Points display (top-right, draggable)
- Freeze button (bottom-left)
- Rewind button (bottom-left)
- Combo multiplier indicator

**Console Screen:**
- Question display with year badge
- 3 answer buttons with hover effects
- Category icon and name
- Glassmorphism container

**Power Indicators:**
- Visual "FROZEN" overlay on timer
- Rewind distortion overlay
- Usage counters

### **Game Over Screen**
- Final score display
- Statistics breakdown (corruption, loops, powers used)
- Ending badge (for Time Loop mode)
- Share/screenshot functionality
- Retry and Google Form feedback buttons
- "Made with ❤️ by Kaustav" credit

### **Modals**
- Achievement Gallery
- Leaderboard (local)
- Screenshot Capture
- Tutorial (first-time boot)

---

## 💻 TECHNICAL ARCHITECTURE

### 📦 **Single-File Design**
- **ONE `index.html` file** (~450KB, 11,000+ lines)
- Embedded CSS (`<style>` tags)
- Embedded JavaScript (`<script>` tags)
- No build process required
- Instant loading

### 🎨 **Pure CSS Implementation**
**CSS Features Used:**
- Custom properties (CSS variables)
- Keyframe animations (100+ animations)
- Backdrop filters (blur, grayscale)
- Clip-path for custom shapes
- Radial/linear gradients
- Mix-blend-mode
- Transform animations
- Glassmorphism effects

**No Image Assets:**
- All visuals are CSS-generated
- Gradients for backgrounds
- Box-shadows for glows
- Borders and filters for effects

### 💻 **Vanilla JavaScript**
**External Dependencies:**
- `html2canvas.min.js` (screenshot capture only)

**Pure JS Features:**
- DOM manipulation
- Event-driven architecture
- Local storage persistence
- Canvas rendering
- Audio API
- RequestAnimationFrame loops
- Procedural generation

### 🎮 **Game Architecture**
**Core Systems:**
- `MusicSystem` - Multi-track audio controller
- `TimerSystem` - Countdown and boss mode logic
- `TimelineIntegrity` - Time Loop corruption tracker
- `DraggableSystem` - UI element repositioning
- `AudioSystem` - SFX synthesis
- `Game` - Main game loop and state
- Achievement tracker
- Leaderboard manager

### ⚡ **Performance**
- Hardware-accelerated CSS transforms
- Efficient particle pooling
- Conditional rendering based on graphics setting
- Optimized animation keyframes
- RequestAnimationFrame for 60fps

---

## 🚀 HOW TO RUN

1. **Clone/Download** the repository
2. **Open `index.html`** in any modern browser:
   - Chrome / Edge (Recommended)
   - Firefox
   - Safari
3. **Click to Start** and allow audio permissions
4. **Play with headphones** for the full horror experience

**No installation. No compilation. No waiting.**

---

## 🎯 HIDDEN FEATURES & EASTER EGGS

**Discoverable Features:**
- Boss Nodes appear every 5th question with green theme
- Draggable UI elements (grab and reposition HUD)
- First-time boot tutorial (clears after localStorage set)
- Multiple ending sequences in Time Loop mode
- Secret achievement trigger (click title 10 times)
- Customizable graphics and safe mode
- Day/Night theme transition in Paradox Mode

**Developer Notes:**
- "The physics in the roulette are tuned for drama" - Code comments
- "Time is the only currency" - Project philosophy
- Hand-tuned color palettes per category
- Obsessive button polish and glint animations

---

## 📊 TECH STACK

**Core Technologies:**
- 🔹 **HTML5** - Structure
- 🔹 **CSS3** - ALL visual effects (blood, glass, glitch, animations)
- 🔹 **Vanilla JavaScript** - Game logic (zero frameworks)

**Libraries:**
- 🔹 **html2canvas** - Screenshot system (only external dependency)

**Fonts (Google Fonts):**
- 🔹 **Orbitron** - Titles and headers
- 🔹 **Rajdhani** - UI and buttons
- 🔹 **VT323** - Terminal/monospace text

**Audio Assets:**
- 🔹 **3 BGM Tracks** - Self-hosted MP3 files
- 🔹 **Procedural SFX** - Generated in-browser

**File Structure:**
```
/game-jam-entry
├── index.html          # THE ENTIRE GAME (11,326 lines)
├── README.md           # This file
├── coin.png            # Logo (1.2MB)
├── gamestart bgm.mp3   # Menu music (3.2MB)
├── gameplay bgm.mp3    # Gameplay music (4.6MB)
└── gameover bgm.mp3    # Death music (2.6MB)
```

---

## 🎥 MEDIA

**Live Link:** [Neuro-Fried: Final Survival](#) *(Add your deployment link)*

**Full Video Overview:** [Watch on YouTube](https://youtu.be/2fnb_pqz9tg)

---

## 🏆 DEVELOPMENT PHILOSOPHY

**"90% of the dev time on JUICE"**

This project is a love letter to **game feel**. Every button click, every particle, every screen shake is meticulously tuned. The goal wasn't just to make a functional trivia game—it was to make something that **FEELS** alive, that **RESPONDS** to you, that makes your heart race.

**Core Principles:**
- Visual feedback for EVERY action
- No placeholders—everything is polished
- Sound design as important as visuals
- Theme cohesion across all screens
- Mobile AND desktop excellence

**No compromises. No shortcuts. Just pure, unfiltered game development insanity.**

---

## 📜 CREDITS

**Design, Code, & Obsessive Polish:** **Kaustav Chowdhury**

Made with **❤️ and too much caffeine**.

**[Under development till 28 Dec]**

---

## 🐛 KNOWN FEATURES (Not Bugs)

- The game is **intentionally loud and intense**
- Screen effects may be overwhelming—**that's the horror aesthetic**
- Time pressure is **relentless by design**
- The AI in Paradox Mode shows no mercy
- Achievement popups don't pause the game (intentional tension)

---

*System Monitor: ONLINE*  
*Signal Strength: 100%*  
*...Entity Watching...*  

**🩸 TIME IS BLEEDING. WILL YOU SURVIVE? 🩸**
