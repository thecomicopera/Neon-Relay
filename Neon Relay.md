# Neon Relay

Neon Relay is a compact cyberpunk puzzle game built as a single-file HTML prototype. You reconnect power through a neon maze by rotating tiles until the uplink reaches every data vault.

## What is it?

This project is a browser-based logic puzzle inspired by circuit-routing games and underground hacker lore. The player rotates glowing tiles to align signal paths, power the network, and unlock each sector.

The game is intentionally lightweight:

- No downloads
- No libraries
- No external services
- Works entirely in the browser as a local HTML file

## How to play

1. Open `neon-relay.html` in a browser.
2. Click a tile to rotate it clockwise.
3. Follow the signal from the pink uplink node.
4. Power every purple vault by aligning adjacent circuit ports.
5. Finish a sector to unlock the next one.

Each tile only works when the connection points face each other. Unused wires are fine; the goal is simply to create a valid route from source to all targets.

## Story

The city is dark, the network is down, and the underground is trying to restore its own communication lines. Each sector represents a different blackout scenario: pirate radio towers, ghost markets, stolen memory archives, and more. Your job is to restore signal flow and bring the city back online.

## Features

- Offline single-file build
- Cyberpunk visual design with neon UI styling
- Logic-based rotation puzzle mechanics
- Multiple sectors with escalating complexity
- Reset, hint, and next-level flow
- Keyboard accessibility using focus + Enter/Space

## Project files

- `neon-relay.html` — complete game logic, art, styling, and puzzle data
- `Neon Relay.md` — project summary / GitHub-friendly description

## Run locally

Double-click `neon-relay.html` or serve the folder with any local static file server, for example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/neon-relay.html
```

## License

This project is intended as a small creative prototype and can be adapted for personal or experimental use.

## Notes

The game is designed as a fast, self-contained prototype. It is intentionally simple and easy to extend if you want to add more sectors, new story beats, or alternate mechanics.
