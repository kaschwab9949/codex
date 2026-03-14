# 🏎️ TURBO GRAND PRIX

### A Detailed HTML5 Canvas Racing Video Game

> Built collaboratively using **Claude**, **ChatGPT**, **Gemini**, **Codex**, and **GitHub**

---

## 🎮 Play the Game

Simply open `index.html` in any modern web browser — no server or dependencies required!

You can also play via GitHub Pages (if enabled).

---

## 🕹️ Controls

| Action | Keys |
|--------|------|
| Accelerate | `W` / `↑` |
| Brake / Reverse | `S` / `↓` |
| Steer Left | `A` / `←` |
| Steer Right | `D` / `→` |
| Handbrake / Drift | `Space` |
| Pause | `Escape` |
| Confirm / Select | `Enter` |

---

## ✨ Features

### 🏁 Racing
- Top-down 2D racing with smooth physics
- 3 unique race tracks with different characteristics
- 5 AI opponent cars with adaptive racing lines
- 3-lap races with position tracking
- Countdown sequence: 3... 2... 1... GO!

### 🚗 Cars
- Multiple selectable cars with unique stats
- Speed, Handling, Acceleration, and Braking attributes
- Drift mechanics with handbrake
- Detailed car rendering with body, windshield, wheels, and spoiler

### 🎨 Visuals
- Detailed track rendering with road, rumble strips, grass, and barriers
- Particle effects: tire smoke, sparks on collision, exhaust fumes
- Tire track marks during drifts
- Minimap showing all car positions
- HUD with speedometer, lap counter, position indicator, and timer

### 🔊 Audio
- Dynamic engine sound (pitch varies with speed)
- Tire screech on drift
- Collision impact sounds
- Countdown beeps
- Victory fanfare

### 📋 Menus
- Title screen with animated branding
- Car selection with stat comparison
- Difficulty selection (Easy / Normal / Hard)
- Race results with final standings and lap times

---

## 🛠️ Technical Details

- **Engine**: Pure HTML5 Canvas + JavaScript
- **Audio**: Web Audio API (no external audio files)
- **Physics**: Custom 2D physics with friction, drift, and collision
- **AI**: Waypoint-following with lookahead and collision avoidance
- **Rendering**: 60fps game loop with delta time
- **File**: Single self-contained HTML file
- **Dependencies**: None — zero external libraries

---

## 🤖 Built With AI Collaboration

This game was created as a collaborative project using multiple AI assistants:

- **Claude (Anthropic)** — Game architecture, core engine, and polished implementation
- **ChatGPT (OpenAI)** — Game design spec, additional features, and code generation
- **Gemini (Google)** — Physics system, AI opponents, and visual effects
- **Codex (OpenAI)** — Code refinement, repository setup, and integration
- **GitHub** — Version control and hosting

---

## 📁 Project Structure

```
codex/
├── README.md          # This file
├── index.html         # The complete game (single file)
├── claude-version.html    # Claude's game implementation
├── chatgpt-version.html   # ChatGPT's game implementation
└── gemini-version.html    # Gemini's game implementation
```

---

## 🚀 How to Run

1. Clone or download this repository
2. Open `index.html` in Chrome, Firefox, Safari, or Edge
3. Select your car, choose a track, and race!

```bash
git clone https://github.com/kaschwab9949/codex.git
cd codex
open index.html
```

---

## 📜 License

This project is open source. Feel free to modify and share!

---

*Made with 🏁 by Kyle Schwab using AI-powered development*
