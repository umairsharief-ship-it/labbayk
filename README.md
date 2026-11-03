# Labbayk Umrah Guide

A single-page, offline-capable Umrah guide (Hanafi), with a Male/Female switch.

## Deploy on GitHub Pages
1. Create a new repository (e.g. `labbayk`) and upload everything in this folder, keeping the `icons/` folder.
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. After a minute the site is live at `https://<your-username>.github.io/labbayk/`.

## Install on each phone (do this at home, on Wi-Fi)
- **iPhone:** open the link in Safari → Share → **Add to Home Screen**. Open it from the home screen icon once.
- **Android:** open in Chrome → ⋮ menu → **Install app** (or Add to Home screen).
- Tap through every tab once so everything is cached, then test in airplane mode.

Note for iPhone: the home-screen app keeps its own saved progress, separate from Safari. Use the same one throughout.

## Updating
Edit `index.html`, then change `VERSION` in `sw.js` (e.g. `labbayk-v2`) and push. Phones get the update the next time they open the app online.
