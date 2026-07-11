# Road trip Naples → Umeå

Installable PWA — itinerary, budget, and travel kit for the Napoli → Umeå → Nordkapp road trip.

## Deploy to GitHub Pages
1. Create a new repo and upload **all files in this folder** to the repo root (`index.html`, `manifest.webmanifest`, `sw.js`, and the icon PNGs).
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pick `main` / `/root`, save.
3. Wait a minute, then open `https://<username>.github.io/<repo>/`.

All paths are relative, so it runs correctly under any subpath. On mobile, use **Add to Home Screen** to install it. The service worker caches pages for offline use.
