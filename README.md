# 🧱 Number Breaker

A browser-based arcade game that combines classic Brickbreaker gameplay with a number/RPG twist. Bricks have hit points — break them strategically, build combos, and clear Target Rows for massive bonus points.

**[▶ Play Now](https://wcantara.github.io/number-breaker/)**

---

## 🎮 How to Play

- **Move your mouse** to control the paddle
- **Click** to launch the ball
- **P or Escape** to pause

### Core Mechanics

| Mechanic | Description |
|---|---|
| **Brick HP** | Each brick displays its hit points. It takes that many hits to destroy it. |
| **Combo Multiplier** | Hit bricks consecutively to build a combo. Every 5 hits raises your damage multiplier (×2 up to ×5). |
| **Target Row** | One row glows gold — clear it entirely for a huge point bonus (1000 × level). |
| **Extra Lives** | Earn +1 life every 2000 points. Clearing the Target Row has a 1-in-3 chance of granting a life. Max 5 lives. |
| **Levels** | Clear all bricks to advance. Higher levels introduce tougher (higher HP) bricks. |

### Ball Speed

Choose your speed before the game starts. Faster speeds are harder but reward more points:

| Speed | Point Multiplier |
|---|---|
| Slow | ×1 |
| Normal | ×1.5 |
| Fast | ×2.5 |
| Turbo | ×4 |

---

## 🛠️ Built With

- [React](https://react.dev/) — UI and game state
- [Vite](https://vitejs.dev/) — build tooling
- Web Audio API — procedurally generated sound effects (no audio files)
- HTML5 Canvas — game rendering

---

## 🚀 Running Locally

Requires [Node.js](https://nodejs.org/).

```bash
# Clone the repository
git clone https://github.com/wcantara/number-breaker.git
cd number-breaker

# Install dependencies
npm install

# Start development server
npm run dev
```

Then open `http://localhost:5173` in your browser.

```bash
# Build for production
npm run build
```

---

## ☕ Support

If you enjoyed the game, consider supporting the project:

- [Buy me a coffee on Ko-fi](https://ko-fi.com/ribozyme)
- [Sponsor on GitHub](https://github.com/sponsors/wcantara)

---

## 👤 Author

**Ribozyme** — [github.com/wcantara](https://github.com/wcantara)

More projects at [wcantara.github.io](https://wcantara.github.io)
