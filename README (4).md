# 🎮 Mini Arcade V3

A browser-based mini arcade collection featuring 5 classic games — built with pure HTML, CSS & JavaScript. No frameworks, no installs, just open and play.

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🕹️ Games

| Game | Description |
|------|-------------|
| 🐍 Snake | Classic snake — eat food, grow longer, don't hit the walls |
| 🏓 Pong | Mouse-controlled paddle vs AI |
| 🧱 Tetris | Rotate and stack falling blocks |
| 🐦 Flappy Bird | Press Space to flap through pipes |
| 🚗 Car Race | Dodge incoming obstacles with arrow keys |

---

## ✨ Features

- 5 playable games in a single HTML file
- Coin system — earn coins based on your score
- Smooth animations via `setInterval` game loops
- Custom alert popup on game over (no browser `alert()`)
- Keyboard listener management — no input conflicts between games
- User session support via localStorage

---

## 🚀 Getting Started

### Option 1 — Just open it

```bash
git clone https://github.com/yahyaberke/mini-arcade.git
cd mini-arcade
open index.html
```

### Option 2 — With login system

This project expects a `login.html` page and a `loggedInUser` key in localStorage. If you're running standalone without a login page, the coin system and logout button won't affect gameplay.

---

## ⌨️ Controls

| Game | Controls |
|------|---------|
| Snake | Arrow keys |
| Pong | Mouse movement |
| Tetris | Arrow keys (↑ rotate, ↓ drop) |
| Flappy Bird | Spacebar to flap |
| Car Race | ← → arrow keys (hold to move) |

---

## 📁 Project Structure

```
mini-arcade/
│
├── index.html    # All 5 games in one file
├── login.html    # Login page (required for full session support)
└── README.md     # Project documentation
```

---

## 🔮 Possible Improvements

- Add high score leaderboard
- Mobile touch controls
- Sound effects
- More games (Breakout, Space Invaders, Memory)
- Difficulty settings per game

---

## 📄 License

This project is licensed under the MIT License.
