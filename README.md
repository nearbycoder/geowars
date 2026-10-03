# Geo Wars: Neon Evolved

A Geometry Wars–inspired twin-stick shooter for the browser, built with [Three.js](https://threejs.org/). Single `index.html`, no build step.

## Play

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8765
```

## Modes

- **Evolved**: the classic endless survival mode
- **Pacifism**: no guns; fly through gates to detonate them
- **Waves**: walls of rockets, one life
- **King**: fire only from inside collapsing safe zones
- **Deadline**: 3 minutes, infinite lives, max score

## Controls

| | Move | Aim / Fire | Bomb | Pause |
|---|---|---|---|---|
| Keyboard + mouse | WASD | Mouse + hold click (or arrow keys) | Space / right-click | Esc |
| Gamepad | Left stick | Right stick | Bumpers / triggers | Start |
| Touch | Left thumb | Right thumb | BOMB button | II button |

## Features

- Spring-mass warping grid, HDR bloom, particle explosions, screen shake and slow-mo
- Enemies: wanderers, grunts, weavers, spinners, snakes, darts, black holes
- Geom multipliers, weapon evolution, and super-state pickups (rapid, spread, pierce, bounce, shield, drone)
- Procedurally synthesized soundtrack and sound effects (Web Audio)
- Per-mode high scores saved locally
