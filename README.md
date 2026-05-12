# Tic Tac Toe — Vanishing Pieces Edition

A browser-based two-player Tic Tac Toe game with a twist: each player can only keep **3 pieces on the board at a time**. Your oldest piece fades out when you place your 4th, and your opponent can reclaim that cell on their next turn.

**Live Demo → [chancer6996.github.io/tictactoe](https://chancer6996.github.io/tictactoe/)**

---

## How to Play

1. Two players take turns on the same device — **X goes first**
2. Click any empty cell to place your piece
3. First to get **3 in a row** (horizontal, vertical, or diagonal) wins

### The Vanishing Rule

- Once you have 3 pieces on the board, placing a 4th causes your **oldest piece to start fading**
- The faded cell is **locked** until your opponent's next turn — then it clears and becomes fair game
- Small **number badges** (1, 2, 3) show the age of each piece — #1 is always next to fade
- A fading piece **does not count** toward a win

This mechanic keeps the board from ever filling up and adds a layer of strategy — you must think about which cells you're about to lose.

---

## Features

- Zero dependencies — single HTML file, works offline
- Persistent score tracker across rounds
- Win highlight animation
- Ghost/pulse animation on pieces about to disappear
- Fully responsive, mobile-friendly layout

---

## Run Locally

No build step required. Just open the file:

```bash
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Or serve it with Python:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

---

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- No frameworks, no dependencies

---

## License

MIT — see [LICENSE](LICENSE)
