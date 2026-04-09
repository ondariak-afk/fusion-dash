# Fusion Dashboard

Mobile-first PWA for tracking your Ford Fusion's maintenance, documents, budget, and fuel.

## Deploy to GitHub Pages (easiest)

1. Create a new repo on GitHub — call it `fusion-dash` or whatever
2. Drop these files in: `index.html`, `manifest.json`, `sw.js`
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**
4. Your app will be live at `https://yourusername.github.io/fusion-dash/`

## Install on your phone

**Android (Chrome):**
- Open the URL in Chrome
- Tap the three-dot menu → "Add to Home Screen"

**iPhone (Safari):**
- Open the URL in Safari (must be Safari, not Chrome)
- Tap the Share button → "Add to Home Screen"

Once installed it works offline — the service worker caches everything.

## Icons (optional)

Drop in `icon-192.png` and `icon-512.png` for a proper home screen icon.
Use any image editor or grab a car emoji and export it at those sizes.
A quick free option: https://favicon.io/emoji-favicons/automobile/

## Local use

You can also just open `index.html` directly in a browser — everything works
except the service worker (which requires HTTPS or localhost).
For local offline use: `npx serve .` and open localhost:3000.
