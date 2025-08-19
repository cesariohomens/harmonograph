# Harmonograph Simulator

Version: 1.0.0

A single‑file React (UMD) app that simulates harmonograph drawings with three models (Simple, Compound, Rotary), animated rendering, multilingual UI, and PNG export at custom resolution.

## Features
- Models:
  - Simple (1 X and 1 Y component)
  - Compound (sum of X components for x(t) and Y components for y(t), no rotation)
  - Rotary (single X/Y with table rotation)
- Animated or fixed color, adjustable line width
- Fit to window, fullscreen, zoom
- Resume drawing across resize/fullscreen
- Export PNG at chosen size (Canvas width/height inputs control export only)
- Languages: EN, PT, FR, ES, IT, DE

## Quick start
- Open `index.html` in a modern browser with internet access (CDN assets are used: React, ReactDOM, Babel, MathJax, Tailwind).
- Adjust parameters on the left, then click Draw or Quick Draw.
- Set “Canvas width/height” to the desired export resolution and click Download PNG.

Notes
- “Canvas width/height” controls the downloaded image size only; on‑screen canvas fills its container.
- Numeric inputs are buffered; values commit on blur or Enter.

## Project structure
- `index.html` – Entire app (UI, rendering, i18n, MathJax, and logic).

## License
MIT – see `LICENSE`.

## Acknowledgments
Inspired by “Harmonograph – A visual guide to the mathematics of music”.
