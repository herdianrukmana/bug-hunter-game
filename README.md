# 🐛 Bug Hunter

**IBM AI Builders Challenge 2025 — IT Track**

A typing-based arcade game where bugs fall from the top of the screen and you must type their error name to destroy them before they reach the Production Server.

---

## 🎮 How to Play

1. Open `index.html` in any modern browser — no server needed, fully offline.
2. Bugs (🐛 NullPointer, SyntaxError, Segfault, etc.) fall from the top.
3. **Type the error word** and press **Space** or **Enter** to squash the bug.
4. If a bug reaches the **SERVER PRODUKSI** line, you lose 1 of 3 lives.
5. Press **Esc** to pause at any time.

---

## ✨ Features

| Feature | Detail |
|---|---|
| 20 bug types | NullPointer, SyntaxError, Segfault, Timeout, 404, StackOverflow, Deadlock, OutOfMemory, and more |
| Combo multiplier | Chain kills to multiply your score (×2, ×3, …) |
| Particle explosions | Neon burst on every kill |
| Screen shake | Haptic-style feedback when a bug gets through |
| Wave system | Difficulty ramps every 30 seconds — faster bugs, faster spawns |
| Sound effects | Fully synthesised via Web Audio API (no audio files) |
| High score | Persisted in `localStorage` across sessions |
| Prefix highlight | Matching characters light up neon-green as you type |
| 4 screens | Start → Game → Pause → Game Over |
| Bahasa Indonesia UI | All in-game text in Indonesian |

---

## 🛠 Technical Details

- **Single file** — `index.html` only, inline CSS + inline JS
- **Zero dependencies** — no frameworks, no libraries, no CDN calls
- **Canvas rendering** — two stacked `<canvas>` elements (arena + particles)
- **Web Audio API** — oscillator-based SFX synthesiser
- **CSS custom properties** — full dark terminal / cyberpunk theme
- **WCAG AA** contrast on all text elements

---

## 🚀 Run Locally

```bash
# Clone and open — no build step required
git clone https://github.com/herdianrukmana/bug-hunter-game.git
cd bug-hunter-game
# Open index.html in your browser
start index.html   # Windows
open index.html    # macOS
```

---

## 📸 Screenshots

> Game arena with falling bugs and neon particle explosions

---

## 📄 License

MIT © Herdian Rukmana
