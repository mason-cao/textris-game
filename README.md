# Textris Pro 🧩📝

Textris Pro is a high-speed browser-based puzzle game that innovates on the classic falling-block genre by fusing spatial strategy with linguistic challenges.

## 📖 Overview

Textris Pro challenges players to multitask between spatial organization and vocabulary recall. Unlike traditional block games, clearing lines requires forming valid English words of 3+ letters. The game features a dynamic physics engine where clearing words triggers a "gravity cascade," allowing for complex chain reactions.

As a "Pro" iteration, this version features an aggressive difficulty curve. As players score points and level up, the drop speed increases drastically, introducing a high-stakes element that demands rapid reflexes and precise planning.

**[Play the Live Demo Here](https://mason-cao.github.io/textris-game/)**

## 🎮 How to Play

**Objective:**
Arrange falling letter blocks to spell words horizontally or vertically. Prevent the stack from reaching the top of the grid.

**Controls:**
* **⬅️ / ➡️ Arrows:** Move the active piece laterally.
* **⬆️ Arrow:** Rotate the piece 90 degrees.
* **⬇️ Arrow:** **Soft Drop** (Slightly accelerate descent).
* **Spacebar:** **Smooth Hard Drop** (Engage hyper-gravity to rocket the piece to the bottom).
* **R Key:** Instant Restart.

**Scoring & Difficulty:**
* **Words:** Valid words explode into particles and award points based on length squared.
* **Gravity:** Remaining blocks fall to fill empty spaces.
* **Leveling:** Every 1,000 points, the game levels up. **Warning:** Speed increases significantly with each level.

## ✨ Technical Features

* **Custom Engine:** Built entirely in Vanilla JavaScript and HTML5 Canvas without external game engines (Unity/Godot).
* **Live Dictionary Integration:** Utilizes the Fetch API to load a 10,000-word MIT dataset, parsed into a JavaScript `Set` for O(1) constant-time lookup performance.
* **Hyper-Gravity Logic:** Implements a smooth "Hard Drop" mechanic that locks user input and accelerates the piece frame-by-frame rather than teleporting it, preventing collision clipping errors.
* **Particle System:** Custom particle class manages visual feedback for word clears.
* **Persistent Data:** Uses `localStorage` to track High Scores across browser sessions.


## 📄 License & Credits

* **Development:** Original code by Mason Cao
* **Wordlist Source:** [MIT 10000 Common Words](https://www.mit.edu/~ecprice/wordlist.10000).

---
