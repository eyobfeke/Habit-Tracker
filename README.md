# Habit Quest

A game-style habit tracker: XP, levels (up to 250) with tiered level-up animations, streaks, badges, monthly and yearly progress charts. Single-page app, no build step, no dependencies. Works offline once opened (installable as an app).

Your data is stored in your browser's localStorage on the device you use.

## Run locally
Open `index.html` in a browser.

## Publish free with GitHub Pages
1. Create a new repository on GitHub and upload all files in this folder.
2. Go to Settings > Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
3. Open the link GitHub gives you (https://YOUR-NAME.github.io/REPO-NAME/) in Chrome.
4. Wait for it to load once, then Chrome menu > Add to Home screen / Install app. After that it works offline.

## Files
- `index.html` the whole app
- `manifest.webmanifest`, `sw.js` make it installable and offline-capable
- `icon.svg`, `icon-192.png`, `icon-512.png` logo
