# Asteroids

A clone of the classic arcade game **Asteroids**, built with plain HTML5 canvas. No dependencies, no bundler.

## Game description

Pilot a spaceship through an asteroid field with screen wrapping (space is toroidal). Destroy asteroids to score points: large ones split into medium ones, and medium ones split into small ones.

## Tech stack

- **HTML5 Canvas** — 2D rendering
- **JavaScript (ES6+)** — all game logic in a single `game.js` file
- No frameworks, no bundler, no dependencies

## How to run

Open `index.html` directly in your browser (double-click), or serve it locally:

```bash
npx serve .
```

Then visit `http://localhost:3000`.

## Controls

| Key       | Action      |
| --------- | ----------- |
| `←` `→`   | Rotate ship |
| `↑`       | Thrust      |
| `Space`   | Fire        |

## Scoring

| Asteroid | Points |
| -------- | ------ |
| Large    | 20     |
| Medium   | 50     |
| Small    | 100    |

## Features

- 3 lives with temporary invincibility on respawn (blinking)
- Asteroids split into smaller fragments when destroyed
- Explosion particles when asteroids are destroyed
