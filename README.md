<p align="center"><img src="favicon.svg" alt="Asteroids arcade-style spaceship icon" width="96"></p>

<h1 align="center">Asteroids</h1>
<p align="center"><em>A clone of the classic arcade game in plain HTML5 canvas. No dependencies, no bundler.</em></p>

<p align="center">
  <a href="#game-description"><img src="https://img.shields.io/badge/type-arcade%20game-6e7781?style=flat-square" alt="Type: arcade game"></a>
  <a href="#tech-stack"><img src="https://img.shields.io/badge/dependencies-none-2ea44f?style=flat-square" alt="Dependencies: none"></a>
  <a href="#how-to-run"><img src="https://img.shields.io/badge/run-open%20index.html-1f6feb?style=flat-square" alt="Run: open index.html"></a>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-Canvas-e34f26?style=flat-square&logo=html5&logoColor=white" alt="HTML5 Canvas">
  <img src="https://img.shields.io/badge/JavaScript-ES6%2B-f7df1e?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript ES6+">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/jacedeno/asteroids-game?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/github/last-commit/jacedeno/asteroids-game?style=flat-square" alt="Last commit">
</p>

## Overview

A clone of the classic arcade game **Asteroids**, built with plain HTML5 canvas. No dependencies, no bundler.

### Game description

Pilot a spaceship through an asteroid field with screen wrapping (space is toroidal). Destroy asteroids to score points: large ones split into medium ones, and medium ones split into small ones.

## Features

- 3 lives with temporary invincibility on respawn (blinking)
- Asteroids split into smaller fragments when destroyed
- Explosion particles when asteroids are destroyed

### Controls

| Key       | Action      |
| --------- | ----------- |
| `←` `→`   | Rotate ship |
| `↑`       | Thrust      |
| `Space`   | Fire        |

### Scoring

| Asteroid | Points |
| -------- | ------ |
| Large    | 20     |
| Medium   | 50     |
| Small    | 100    |

## Tech stack

- **HTML5 Canvas** — 2D rendering
- **JavaScript (ES6+)** — all game logic in a single `game.js` file
- No frameworks, no bundler, no dependencies

## Getting started

### How to run

Open `index.html` directly in your browser (double-click), or serve it locally:

```bash
npx serve .
```

Then visit `http://localhost:3000`.

## License

MIT — see [LICENSE](LICENSE).

---

<p align="center">
  Built by <b>Jose Cedeno</b> ·
  <a href="https://geekendzone.com">geekendzone.com</a> ·
  <a href="https://www.linkedin.com/in/joseangelcedeno/">LinkedIn</a>
</p>
