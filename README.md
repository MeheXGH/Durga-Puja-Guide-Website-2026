# Durga Puja Pandal Hopping Guide 2026 — PWA

This is a GitHub Pages-ready version of the supplied single-file website. It preserves the existing pandal, food, transit and auto-stand data and adds install metadata, app icons, a service worker, a mobile layout patch and an install button.

## Files

- `index.html` — existing app UI, data, CSS and JavaScript, with PWA/mobile additions
- `manifest.webmanifest` — install name, icons, start URL and standalone display mode
- `sw.js` — caches the app shell and supports an offline fallback for the HTML page
- `icons/` — app icons for Android, maskable launchers and iOS home screen

## Deploy to the existing GitHub Pages project

1. Download and unzip this project.
2. Open your repository: `https://github.com/mehexgh/Durga-Puja-Guide-Website-2026/`.
3. Back up the current repository or create a branch before replacing files.
4. Upload/commit `index.html`, `manifest.webmanifest`, `sw.js`, and the complete `icons` folder to the repository root (same level as the current `index.html`).
5. Commit to the branch configured in **Settings → Pages**.
6. Wait for GitHub Pages to finish deploying.
7. Open the live website over HTTPS. In Chrome DevTools → Application, verify Manifest and Service Workers. In Network, confirm manifest, sw.js and icon files return 200.
8. On Android Chrome, open the browser menu and choose Install app / Add to Home screen. The in-page Install button appears when Chrome fires `beforeinstallprompt`. On iPhone, use Safari → Share → Add to Home Screen; the in-page button explains the iOS steps.

## Important notes

- This site uses relative paths (`./`) so it works at the GitHub Pages project URL, not only at the domain root.
- The service worker caches the local app shell and icons. It does **not** cache Leaflet map tiles or remote CDN files, so the interactive map may need an internet connection. Do not promise offline maps until tiles and libraries are deliberately designed and tested for offline use.
- If the old app stays cached after a deployment, change `CACHE_NAME` in `sw.js` (for example, `puja-guide-shell-v2`) and reload the site.
- Test on actual Android and iPhone devices before festival day. Browser installation behavior varies by browser and platform.
- Keep a backup of the original `index.html` before replacing it.

## Existing features retained

Interactive Leaflet map, 18 curated pandals, food hubs, transit/auto stops, filters, visited checklist using localStorage, GPS location, custom spot form and Google Maps navigation links.


## Approved Durga Maa logo
The approved generated artwork is used unchanged for the app's header logo. Resized copies are used for PWA, Apple, and favicon sizes. The full artwork is stored at `icons/durga-maa-logo.png`.
