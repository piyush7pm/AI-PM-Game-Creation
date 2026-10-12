# Memory Game (GHCP)

## What this project does
This project is a browser-based memory matching game. The player flips cards to find matching emoji pairs, tracks moves and time, and tries to complete the board with the fewest moves possible.

It includes:
- A 4x4 board and a larger 6x6 board option
- Move count and timer tracking
- Star-based rating feedback
- Best-score persistence using browser localStorage
- Keyboard and mouse interaction support
- A win modal that displays final stats

## What the repo stands for
The repo name is `memory-game-GHCP`.

In practical terms, this appears to be a small personal/demo project for a memory game, with `GHCP` likely referring to GitHub Copilot / GitHub Copilot Playground-style development context, depending on the environment it was created in. The main functionality is the memory game itself, not an enterprise application or backend service.

## Architecture and implementation
This repo is intentionally very lightweight:
- One HTML file: `memory-game.html`
- CSS is embedded in the same file for styling, layout, and card flip animations
- JavaScript in the same file handles:
  - game state
  - shuffle logic
  - card matching logic
  - timer and move tracking
  - win detection
  - local score saving

## Why it exists
This is a classic front-end demo project meant to showcase:
- DOM manipulation in vanilla JavaScript
- CSS animations and responsive design
- browser localStorage usage
- simple game logic in a single-page app

## Summary
This repo is a small, self-contained memory game built with plain HTML, CSS, and JavaScript. It is designed to be easy to run in a browser and demonstrates classic game logic and front-end interactivity. The `GHCP` portion of the repo name most likely reflects the GitHub Copilot-assisted context in which it was created.
