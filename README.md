# 🎮 Super Mario Retro Chronicles

[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6_Modules-yellow.svg)]()
[![Audio](https://img.shields.io/badge/Web_Audio-API_Sound_Synth-brightgreen.svg)]()
[![Layout](https://img.shields.io/badge/Layout-Edge_to_Edge_Widescreen-blue.svg)]()

A premium, fully responsive 2D retro Mario platformer game designed to run directly in any modern web browser. Built entirely from scratch using vanilla web technologies, featuring a clean fullscreen layout, custom sound synthesis, and multiple game levels.

👨‍💻 **Project Owner**: Pratik Thorat

---

## 🚀 Key Showcase Features

### 🖥️ 1. Edge-to-Edge Widescreen Fullscreen Layout
- **Zero Black Bars**: Scaled to occupy 100% of the screen width (`100vw`) and height (`100vh`) dynamically on any desktop monitor, tablet, or mobile phone.
- **Native Fullscreen API**: Automatically requests HTML5 fullscreen mode upon starting the game or selecting a level for an arcade experience.
- **Mobile Responsive HUD**: Game overlays, controls, and active status display scale seamlessly on top of the fullscreen viewport.

### 👑 2. Bowser Boss Chamber & Bridge Collapse (World 1-3)
- **World 1-3 Castle Level**: Lava pits (instantly deadly), rotating Firebar hazards, and Bowser's boss chamber.
- **Bowser Boss AI**: Boss jumps, breathes wavy fireballs, and throws hammers in arcs to defend his bridge.
- **Bridge Collapse Trigger**: Jump past Bowser and hit the Golden Axe to collapse the bridge tile-by-tile, sending Bowser plunging into the lava.
- **Ending Cinematic Dialogue & Credits**: Auto-walks Mario to Princess Peach, triggers custom chat bubbles, retro fireworks particles, and scrolls retro game credits.

### 🎨 3. Procedural Art & Audio Engines
- **Procedural Graphics (`js/sprites.js`)**: Pixel art sprites compiled programmatically at runtime on HTML5 canvases. Zero external image assets required for instant loading and perfect scaling.
- **8-Bit Sound Synth (`js/audio.js`)**: Loops chiptune tracks and generates retro sound effects (jumps, coin pickups, power-ups, damage, game over) using the browser's Web Audio API.
- **Parallax Background**: Multi-layered background scrolling (clouds, mountains, bushes, crystals) simulating visual depth.

---

## 🎮 Game Controls
- **Desktop Keyboard**: 
  - `A / D` or Arrow keys to move left/right.
  - `W / Space` to jump.
  - `S` to crouch.
  - `J / Shift` to run fast and shoot fireballs.
- **Mobile Touch Controls**: Full interactive virtual D-pad (◀, ▲, ▼, ▶) and action buttons (A & B) for touchscreen navigation.

---

## 🛠️ How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ipverse1918/Mario-Level-2026-version.git
   cd Mario-Level-2026-version
   ```
2. **Start a local web server** (e.g. using Python):
   ```bash
   python -m http.server 8000
   ```
3. **Open the game** in your browser:
   - Navigate to `http://localhost:8000`.
