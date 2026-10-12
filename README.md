# Classic Browser Game Collection

This repository contains a small collection of browser-based mini games built with plain HTML, CSS, and JavaScript. Each game is designed to run as a single standalone file without any external dependencies.

## Included Games

### 1. Memory Game
A classic card-matching game where players flip cards to find matching pairs.

Features:
- 4x4 and 6x6 board modes
- Move counter and timer
- Star-based rating system
- Best-score persistence using localStorage
- Keyboard and mouse support
- Responsive dark mode

File: `memory-game.html`

### 2. Tic-Tac-Toe
A traditional three-in-a-row strategy game for two players.

Features:
- 3x3 game board
- X and O turn tracking
- Win and draw detection
- Scoreboard across rounds
- New round and reset score actions
- Light and dark theme support
- Responsive layout

File: `tic-tac-toe.html`

## Project Purpose

This project is designed to showcase how familiar childhood games can be recreated using only front-end web technologies. It is ideal for:
- learning DOM manipulation
- practicing vanilla JavaScript game logic
- building polished browser games without frameworks
- quick prototyping and experimentation

## How to Run

Open any game file directly in a browser:

```bash
memory-game.html
```

or

```bash
tic-tac-toe.html
```

You can also serve the folder locally for a cleaner browser experience:

```bash
python -m http.server 8000
```

Then visit:
- `http://localhost:8000/memory-game.html`
- `http://localhost:8000/tic-tac-toe.html`

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Local Storage for simple persistence

## Notes

These games are intentionally lightweight and self-contained so they are easy to understand, customize, and extend.
