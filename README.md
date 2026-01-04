# textris-game
# Textris Pro 🧩📝

A browser-based puzzle game that combines the falling-block mechanics of Tetris with the vocabulary skills of Scrabble.

Link (In Progress): https://mason-cao.github.io/textris-game/
## 🎮 How to Play

Blocks fall from the top of the screen, each containing a random letter. Your goal is to arrange them to spell valid English words.

* **Move:** Left/Right Arrow Keys
* **Rotate:** Up Arrow Key
* **Soft Drop:** Down Arrow Key
* **Restart:** Press 'R'

### Rules
1.  **Form Words:** Create words of **3 or more letters** horizontally or vertically.
2.  **Clear Blocks:** Valid words explode and disappear, giving you points.
3.  **Gravity:** Unlike classic Tetris, blocks float down to fill empty spaces, potentially creating chain reactions.
4.  **Game Over:** The game ends if the stack reaches the top of the screen.

## ✨ Features

* **Dynamic Dictionary:** Fetches a 10,000-word dictionary (MIT Wordlist) in real-time using the Fetch API.
* **Physics Mechanics:** "Sticky" gravity allows for complex board manipulation and chain reactions.
* **Progression System:** The game speeds up as you score points and level up.
* **Visual Effects:** Particle explosions when words are cleared and a "Next Piece" preview window.
* **High Score:** Uses LocalStorage to save your best score even after closing the browser.

## 🛠️ Built With

* **HTML5 Canvas** (Rendering the game grid and particles)
* **Vanilla JavaScript** (Game logic, collision detection, and state management)
* **CSS3** (Styling the UI layout)
* **External API:** Uses `allorigins.win` as a CORS proxy to fetch the wordlist.


## 📄 Credits

* Wordlist provided by [MIT](https://www.mit.edu/~ecprice/wordlist.10000).
* Game logic built from scratch in JavaScript.
