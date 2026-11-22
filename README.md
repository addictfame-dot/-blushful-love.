# Blushful Love — Website / PWA

A mobile and desktop responsive romantic book editor.

## Publish on GitHub Pages (phone-friendly)
1. Create/open your `blushful-love` repository.
2. Upload **the contents of this `blushful-love` folder** into the repository root (index.html, src/, icons, manifest, etc.).
3. Go to Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. Wait for the Pages deployment, then visit `https://YOUR_USERNAME.github.io/blushful-love/`.
5. On Android Chrome use menu → Add to Home screen / Install app. On desktop Chrome/Edge use Install app if offered.

## Local preview
Serve this folder with a static HTTP server, for example `python -m http.server 8000`, then open `http://localhost:8000`. Opening index.html directly may prevent service worker and update checks.

## Included
- Cover title, color, custom cover image, theme and page color
- Two-page editing, formatting buttons, contents navigation, basic animated flip
- Image upload/clipboard paste, dragging, width/brightness/rotation sliders
- Local browser storage, JSON import/export, installable PWA shell
- Manual version check against version.json

## Important limitations
- Book is CSS-perspective 2.5D, **not** physically simulated photorealistic Three.js geometry.
- Spellcheck depends on browser; grammar AI and synonyms API are **not implemented**.
- The version checker is manual and compares version.json to 1.0.0; no push notifications or automatic GitHub release installer.
- LocalStorage is per browser/device; no cloud synchronization. Photos stored as base64 can fill browser quota. Export JSON backups regularly.
- HTML editing uses browser execCommand (legacy) and should be replaced with a rich text editor for production.
- Uploaded JSON is not sanitized; import only files you trust.
