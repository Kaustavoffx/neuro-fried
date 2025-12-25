# 🧠 NEURO-FRIED: FINAL SURVIVAL

> **"Time is the only currency. And yours is bleeding out."**

Yo! This is **NEURO-FRIED**, my submission for the jam. I didn't just want to make a trivia game; I wanted to make a **panic attack that feels like a rave**.

I spent **90% of the dev time on JUICE**.

**🔥 What Makes This Insane:**
- **Visual Overload**: Every correct answer triggers a massive particle explosion and screen shake. It's not just "+10 points", it's a tactile **CRUNCH** that makes your brain go "brrr".
- **The "God-Tier" Engine**: No game engine. No libraries. No pre-made assets. Everything you see—the nebula, the stars, the UI glow—is **pure, handmade math** rendered on a Canvas.
- **High Stakes**: There is no health bar. **Time is your health**. Every second you hesitate, you die a little. Every wrong answer? Massive time penalty. You are constantly on the edge of your seat.

---

## 🕹️ GAME MODES

### 1. 🎯 **OWN LUCK (Standard Mode)**
- Classic survival trivia with time-based gameplay
- **Time Powers**: Freeze and Rewind abilities to manipulate the clock
- Manage your score multiplier to maximize your "Aura"
- Every correct answer adds time; every wrong answer bleeds it away
- Pure skill-based progression with no second chances

### 2. 🌀 **TIME LOOP (Dream Mode)**
- Death is not the escape—you loop back instead
- Features random **Dream Sequences** that distort reality
- If you fail, you loop back with a penalty, trapped until you stabilize the timeline
- Psychological horror elements intensify with each loop
- The game remembers your failures

### 3. ⚔️ **PARADOX MODE (Sanity meter)**
- Battle against an **Time Loop** in a race to answer first
- **Sanity Meter** replaces Health—wrong answers damage your mental state
- **LOGIC INVERSION**: When text glitches, pick the **WRONG** answer to survive
- **Chaos Level** rises over time, increasing difficulty
- No timer—pure head-to-head competition
- The AI learns and adapts to your patterns

---

## 🎮 CORE GAMEPLAY COMPONENTS

### ⏰ **Time Mechanics**
- **Sanity Meter**: Your life is literally the clock ticking down
- **Time Gain/Loss System**: +5s correct, -5s wrong (adjustable in code)
- **Time Bar Visualization**: Animated progress bar with color-coded warnings
- **Countdown Anxiety**: Visual and audio cues as time runs low

### 🔮 **Time Powers (Consumable Abilities)**
- **❄️ FREEZE**: Stops the timer for 5 seconds (limited uses)
  - Visual: Cyan glow, grayscale effect, screen frost overlay
  - Audio: Procedural freeze sound effect
  - Timer panel shows "FROZEN" indicator with pulsing glow
  
- **⏪ REWIND**: Regain 10 seconds of lost time (limited uses)
  - Visual: Screen distortion lines, reverse particle flow
  - Audio: Tape rewind effect
  - Glitch screen animation during rewind

### 📊 **Scoring & Progression**
- **Points System**: Base score + multiplier bonuses
- **Combo Multiplier**: Chain correct answers for higher scores
- **Aura Meter**: Visual representation of player skill/performance
- **High Score Tracking**: Local storage persistence

### 🎯 **Question System**
- **Multi-Category Questions**: Code, Space, Finance, Social, Gaming
- **Dynamic Difficulty**: Questions adapt based on performance
- **Category-Specific Themes**: Each category changes visual theme/colors
- **Answer Validation**: Real-time feedback with visual effects

---

## 🎨 VISUAL EFFECTS & JUICE

### 🌌 **Procedural Canvas Rendering**
- **Nebula Background**: Real-time mathematical rendering (no images)
- **Particle System**: 1000+ particles reacting to game state
  - Calm particles during normal gameplay
  - Explosive particles on correct answers
  - Reverse-flow particles during rewind
- **Starfield**: Parallax scrolling star layers with depth
- **Dynamic Lighting**: Color-shifting based on game mode/category

### 💀 **Horror Visual Effects**
- **Blood Red Ambient**: Pulsing red glow from screen edges
- **Blood Veins Overlay**: Creepy pulsing vein patterns
- **Blood Drip Effect**: Subtle dripping from top of screen
- **CRT Scanlines**: Old-school terminal aesthetic
- **Screen Shake**: Triggered by wrong answers and critical moments
- **Glitch Screen**: Chromatic aberration and skew effects
- **Anxiety Pulse**: Intensifying red glow as time runs out

### ✨ **UI Polish**
- **Glassmorphism**: Frosted glass UI panels with backdrop blur
- **Text Shaders**: Royal gold and chrome metallic text effects
- **Button Glint**: Animated light sweep across buttons
- **Typewriter Effect**: Character-by-character text reveal with cursor
- **Eerie Float Animation**: Subtle floating motion on UI elements
- **Vignette Effect**: Dramatic edge darkening

### 🎭 **Special Transitions**
- **Boot Tunnel Animation**: Octagonal warp-speed tunnel on game start
  - Metallic sheen, neon glow, spiral effect
  - Mind-blowing initial boot sequence
- **Black Hole Implosion**: DOM elements distort into singularity on exit
- **Fade from Darkness**: Cinematic fade transitions between screens
- **Screen Distortion**: Physics-based warp effects

---

## 🔊 AUDIO SYSTEM

### 🎵 **Adaptive BGM Engine**
- **3-Track Dynamic System**:
  - `gamestart bgm.mp3`: Intro ambience for menus
  - `gameplay bgm.mp3`: High-tension loop during gameplay
  - `gameover bgm.mp3`: "Signal Lost" theme for death screen
- **Seamless Transitions**: Cross-fade between tracks based on game state
- **Smart Volume Ducking**: Automatic volume adjustment during SFX
- **Loop Management**: Perfect looping with no gaps

### 🎧 **Procedural Sound Synthesis**
- **Typing Sounds**: Generated on-the-fly to sound unnervingly organic
- **UI Click Sounds**: Synthesized interaction feedback
- **Power-Up Effects**: Freeze/Rewind audio cues
- **Horror SFX**: Glitch noises, distortions, ambient dread
- **Success/Fail Chimes**: Instant audio feedback for answers

### 🔇 **Audio Controls**
- **Sound Toggle**: Mute/unmute all game sounds
- **Persistent Settings**: Audio preferences saved to local storage
- **Headphone Recommendation**: Prominent warning on start screen for optimal experience

---

## 🎛️ CUSTOMIZATION & SETTINGS

### 🌈 **Theme System**
- **Multiple Visual Themes**: 5+ color schemes (Horror, Finance, Code, Space, Social, Gaming)
- **Category-Based Themes**: Auto-switch based on question category

### ⚙️ **Graphics Options**
- **Graphics **: Performance optimization for lower-end devices
- **Safe Mode**: Reduces intense visual effects for accessibility
- **Particle Density Control**: Adjustable particle count
- **Effect Intensity**: Customizable screen shake and glitch strength

### 📱 **Responsive Design**
- **Desktop Friendly**: Optimized for keyboard navigation
- **Adaptive Layout**: UI scales to screen size
- **No Asset Loading**: Instant load times—zero external dependencies

---

## 🎬 SCREENS & UI FLOW

### 📺 **Title Screen**
- "Click to Start" overlay with pulsing text
- Headphone recommendation warning
- Ambient particle background
- Audio initialization

### 🎰 **Fate Selection (Mode Select)**
- 3 game modes with descriptions
- Rules overlay with rounded card design
- Visual preview of each mode
- Animated mode selection

### 🎮 **Game Screen**
- **HUD Elements**:
  - Timer panel (top-left by default)
  - Points display (top-right)
  - Power-up buttons (Freeze/Rewind)
  - Progress indicators
- **Console Screen**: Question display with bezel-free design
- **Answer Buttons**: 4 options with hover effects
- **Real-time Feedback**: Instant visual response

### 💀 **Game Over Screen**
- Final score display
- Statistics breakdown
- Retry button with glint effect
- "Made with ❤️ and too much caffeine by Kaustav" credit
- Google Form feedback integration
- Screenshot capture feature (html2canvas)

---

## 🛠️ TECHNICAL ARCHITECTURE

### 📦 **Single-File Design**
- **Zero Dependencies**: Everything in one `index.html` file
- **No Build Process**: Just open and play
- **File Size**: Tiny (~450KB) despite all features
- **Instant Loading**: No asset downloads required

### 🎨 **Pure CSS Wizardry**
- All visual effects are CSS3 animations
- No pre-rendered images (except optional coin.png)
- Glassmorphism, gradients, blend modes
- 100+ custom keyframe animations

### 💻 **Vanilla JavaScript**
- No frameworks, no libraries (except html2canvas for screenshots)
- Pure DOM manipulation
- Event-driven architecture
- Object-oriented game logic

### 🎯 **Performance Optimizations**
- RequestAnimationFrame for smooth 60fps particles
- CSS transforms for hardware acceleration
- Efficient particle pooling
- Conditional rendering based on graphics settings

---

## 🚀 HOW TO RUN

1. **Clone or Download** the repository
2. **Open `index.html`** in any modern browser (Chrome, Edge, Firefox recommended)
3. **Click to Start** and grant audio permissions
4. **Play it loud. Play it fast. Don't let the timeline collapse.** 🩸

**No installation. No compilation. No waiting.**

---

## 🎯 HIDDEN FEATURES (Go Find Them! 😁)

- **Customizable Components**: Some game parameters are adjustable in the code
- **Easter Eggs**: Visual and audio surprises triggered by specific actions
- **Secret Themes**: Unlockable color schemes
- **Developer Notes**: Commentary scattered in the code

---

## 📊 TECH STACK

**Core:**
- 🔹 **HTML5** (Structure)
- 🔹 **Vanilla CSS3** (All visual effects)
- 🔹 **Vanilla JavaScript** (Game logic)

**Libraries:**
- 🔹 **html2canvas**: Screenshot capture (only external dependency)

**Fonts:**
- 🔹 **Orbitron** (Titles)
- 🔹 **Rajdhani** (UI)
- 🔹 **VT323** (Terminal/Data)

**Assets:**
- 🔹 **3 BGM Tracks** (Self-hosted)
- 🔹 **Procedural SFX** (Generated in-browser)

---

## 🎥 MEDIA

**Live Link**: [Neuro-Fried: Final Survival](#) *(Add your link here)*

**Full Video Overview**: [Watch on YouTube](https://youtu.be/2fnb_pqz9tg)

---

## 🏆 DEVELOPMENT PHILOSOPHY

**"90% of the dev time on JUICE"**

This project is a love letter to game feel. Every button click, every particle, every screen shake is meticulously tuned. The goal wasn't just to make a functional trivia game—it was to make something that **feels** alive, that **responds** to you, that makes your heart race.

**No compromises. No shortcuts. Just pure, unfiltered game development insanity.**

---

## 📜 CREDITS

**Design, Code, & Obsessive Polish**: **Kaustav Chowdhury**

Made with **❤️ and too much caffeine**.

**[Under development till 28 Dec]**

---

## 🐛 KNOWN FEATURES (Not Bugs)

- The game is **loud and intense** by design
- Screen effects may be overwhelming—that's the point
- Time pressure is **relentless**—adapt or perish
- The AI in Paradox Mode is **ruthless**
- Some Easter eggs are **very** well hidden

---

*System Monitor: ONLINE*  
*Signal Strength: 100%*  
*...Entity Watching...*  

**🩸 TIME IS BLEEDING. WILL YOU SURVIVE? 🩸**
