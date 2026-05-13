# Website — CLAUDE.md

Single static landing page for The Bull Contracts platform.

## File
- `index.html` — self-contained, no build step, open directly in browser

## Deploy
```bash
git subtree push --prefix website public main
```
`public` remote → https://github.com/Ofia/the_bull_legal_website.git
Live at → https://ofia.github.io/the_bull_legal_website/

## Design
Follows the ARCHI dark theme (see root CLAUDE.md):
- Background: `#0d0d10`
- Accent: `#b38600` (gold)
- Fonts: Space Grotesk + Space Mono (Google Fonts)
- Node colors match the app exactly (`#FFBD2E`, `#0A84FF`, `#00CA4E`, `#FF5F5A`)

## Background animation
Canvas-based 2D node network — mimics the app's 3D NodeCluster.
Dots drift, links appear/fade by proximity, each node has a soft glow.
All in a `<script>` block at the bottom of `index.html`.
