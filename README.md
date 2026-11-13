# Cerebella Demo

© Alexander Riccardi · Demo version only · Not for patient treatment.

A standalone demo of Cerebella. It shows seven exercises on six background themes, using the same exercise and background engine as the full app. Each exercise runs for 15 seconds.

## Files
- `index.html` – the demo app
- `manifest.webmanifest`, `sw.js`, `icon-*.png` – let the demo be installed on iPhone, Android and desktop, and work offline
- `.nojekyll` – tells GitHub Pages to serve the files as they are

## Hosting on GitHub Pages
1. Upload every file to the root of the repository.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The demo will be live at `https://<username>.github.io/<repo>/`.

The install button on the home page works once the demo is on GitHub Pages (it needs a real https address).
