# Dragon Lair Simulator

A Three.js dragon flight simulator. You are an ancient mountain dragon.

## Features

- **Flight model** — flap for thrust and lift, bank, pitch/yaw with mouse, glide and ground collision
- **Mountain lair** — procedural terrain with snow peaks, rock, and grassland
- **Treasure hoard** — gold piles in your cave
- **Raid towns** — fly over villages and breathe fire (F) for gold
- **Steal sheep** — pick them up (E) and drop them in the cave (G)
- **Recover dragon eggs** — find nests, collect the eggs, return them home

## Controls

| Input | Action |
|-------|--------|
| Mouse | Look / pitch & yaw (click canvas to lock) |
| W / Space | Flap wings |
| S | Brake |
| A / D | Bank left / right |
| E | Pick up sheep or egg |
| G | Drop cargo (near cave = hoard it) |
| F | Breathe fire / raid town |
| Esc | Unlock mouse |

## Play

Open the live page after enabling GitHub Pages, or open `index.html` locally in a modern browser.

## Tech

- Three.js (CDN)
- Single-file, no build step
- Procedural mesh dragon + heightmap terrain

Created for fun dragon simulation.
