# First Blood Dynamic Scenarios — PWA

An unofficial fan-made web companion. This package includes the scenario app, manifest, offline service worker, and icons.

## Publish using GitHub Pages
1. Create a **public** GitHub repository, e.g. `first-blood-scenarios`.
2. Upload the **contents of this folder** to the repository root (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`). Do not upload only the ZIP.
3. In **Settings → Pages**, set Source to **Deploy from a branch**, Branch `main`, folder `/ (root)`, and Save.
4. Wait for GitHub Pages to finish publishing. Open `https://YOUR_USERNAME.github.io/first-blood-scenarios/`.
5. On Android Chrome, open the URL, then choose **Install app** or **Add to Home screen** from the browser menu. On iOS Safari, use **Share → Add to Home Screen**.

## Updates
Replace changed files and increase the version in `sw.js` (`first-blood-pwa-v2`, etc.) so offline caches refresh. Browser updates may take a reload.

## Notes
- Offline access is available after a successful first online visit.
- Battle state is stored in each browser's local storage; it is not synchronized between devices.
- GitHub Pages uses HTTPS, required for service workers.
- This app contains map and rules content derived from a user-provided Para Bellum PDF. Before public redistribution, obtain appropriate permission or replace copyrighted material with independently created assets and summaries. This is not an official Para Bellum product.
