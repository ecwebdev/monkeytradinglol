# Monkey Trading Desk 🐒🍌

A tiny 3D room you can orbit: a monkey sits at its desk, watching new token pairs launch on a live-updating screen, checking the chart, typing, and occasionally aping in.

Single self-contained `index.html` — no build step. Uses [three.js](https://threejs.org/) r147 from a CDN.

## Run it

- **Locally:** open `index.html` in a browser (or `npx serve .`).
- **GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / root. The page will be live at `https://<your-username>.github.io/<repo-name>/`.

## Controls

- Drag to rotate · scroll or pinch to zoom · right-drag to pan
- Camera presets: Room, Over shoulder, Face, Bed, Top, Auto-rotate

## What's in the scene

- Animated monkey with IK arms, blinking, saccades, ear twitches and a swaying tail
- Main monitor: fake "new pairs" feed (New / Bonding / Migrated columns) drawn to a canvas texture
- Side monitor: live candlestick chart
- Desk lamp, mug with steam, bananas, plant, bookshelf, bed, wardrobe, jungle-night window

All tokens, prices and trades on screen are randomly generated — nothing connects to a real market.
