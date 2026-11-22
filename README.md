# Blushful Love — Romantic Book Studio (visual redesign)

A static GitHub Pages-ready project. Upload **the contents of this ZIP** to the root of your `blushful-love` repository and enable Settings → Pages → Deploy from branch → main / root.

## Included
- Preview-inspired burgundy, blush, gold desktop layout and responsive mobile UI
- Editable page text, formatting controls, table of contents and page navigation
- Cover/title/theme/page color changes and custom cover upload
- Photo upload and clipboard paste, drag, width, brightness and rotation
- Local device storage, JSON export/import, basic page flip, PWA manifest

## Honest limitations
This is an upgraded visual implementation, **not** a photorealistic Three.js 3D engine. Page turns are CSS-based; advanced grammar corrections, synonyms, photo cropping and cloud sync are not implemented. Spellcheck is browser-provided. Google Fonts require an internet connection; fallback fonts work offline. Personal photos saved in browser storage may exceed storage limits; export backups regularly. Do not upload private photos or letters to a public GitHub repository.

## Deploy
1. Extract ZIP and upload its contents (not the enclosing folder) to GitHub repo root.
2. Confirm `index.html`, `src/`, `manifest.webmanifest` are at root.
3. Settings → Pages → main → / (root).
4. Wait for deployment and hard-refresh website; existing service worker may cache an older version.

## Testing
Static source checked; interactive browser tests and cross-device tests not performed.
