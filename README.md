# Asteroids JS

A classic Asteroids arcade game built in a single HTML file using vanilla JavaScript and the HTML5 Canvas API. No dependencies, no build step — just open `index.html` in a browser.

## Play

[**Play it here →**](https://jcodling.github.io/asteroids-js)

Or clone and open locally:

```
git clone https://github.com/jcodling/asteroids-js.git
cd asteroids-js
open index.html
```

## Controls

| Key | Action |
|-----|--------|
| ↑ | Thrust |
| ← → | Rotate |
| Space | Shoot |

Press any key on the demo screen to start playing.

## Features

- **3 asteroid sizes** — large splits into 2 medium, medium into 2 small
- **Scoring** — 20 / 50 / 100 pts by size; extra life every 100,000 pts
- **High score** — persisted via `localStorage`
- **Procedural audio** — all sounds synthesized via the Web Audio API (thrust, shoot, explosions, extra life jingle)
- **Particle effects** — on asteroid and ship destruction
- **Elastic collisions** — asteroids bounce off each other with mass-based physics
- **AI demo mode** — an autopilot plays the game on the attract screen using predictive aim

## Tech

- HTML5 Canvas
- Web Audio API
- Vanilla JavaScript (no frameworks, no build tools)
