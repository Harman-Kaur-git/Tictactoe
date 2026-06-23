# ❌⭕ Tic Tac Toe

A classic **Tic Tac Toe** game built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks, no libraries, just vanilla web. Play against a friend in your browser, instant and lightweight.

---

## 🌍 Live Demo

🎮 **[Play Now →]( https://tictactoedeployed.netlify.app)** 

---

## 🚀 Features

- 🎮 **2 Player Mode** — Play locally against a friend (X vs O)
- 🏆 **Win Detection** — Instantly detects all 8 winning combinations
- 🤝 **Draw Detection** — Handles draw condition when board is full
- 🔄 **Restart / Reset** — Reset the board anytime without page reload
- ✨ **Winning Highlight** — Highlights the winning cells on victory
- 📱 **Responsive Design** — Works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (ES6+) |

> Zero dependencies. No npm. No build step. Just open and play.

---

## ▶️ Getting Started

No install needed. Just clone and open.

```bash
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
```

Then open `index.html` in your browser — done.

---

## 🧠 Game Logic

- Board is a **3×3 grid** tracked as an array of 9 cells
- Players alternate turns — **X always goes first**
- After every move, all **8 win patterns** are checked against current state
- If all 9 cells filled with no winner → **Draw**
- Winning cells get **highlighted**, game locks until reset

```js
// Win combinations checked after every move
const WIN_PATTERNS = [
  [0, 1, 2], [3, 4, 5], [6, 7, 8], // rows
  [0, 3, 6], [1, 4, 7], [2, 5, 8], // columns
  [0, 4, 8], [2, 4, 6]             // diagonals
];
```

