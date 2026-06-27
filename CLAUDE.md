# Asteroids

Vanilla HTML5 Canvas game, no build step.

## Run

Open `index.html` in browser, or:
```bash
npx serve .
```

## Stack

- `index.html` — page + canvas
- `game.js` — all game logic (Ship, Bullet, Asteroid, Particle, game loop)
- `favicon.svg` — arcade ship icon

## Notes

- Space = shoot, arrows = move/rotate
- 3 lives, levels scale asteroid count
- No dependencies, no bundler
