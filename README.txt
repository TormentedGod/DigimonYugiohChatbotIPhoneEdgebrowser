FUGGLER FACTORY — GITHUB PAGES PACKAGE

UPLOAD THESE THREE FILES TO THE SAME FOLDER IN YOUR GITHUB REPOSITORY:
  index.html
  sw.js
  manifest.webmanifest

PUBLISHING:
1. Create or open your GitHub repository.
2. Upload all three files to the repository's publishing folder (usually the repository root).
3. In Settings > Pages, choose Deploy from a branch, select your branch and folder, and save.
4. Wait for GitHub Pages to publish, then open the HTTPS Pages address on your iPhone.
5. In Safari, use Share > Add to Home Screen if you want an app-like home-screen shortcut.

MOBILE NOTES:
- The chat interface, settings, and browser-local saves are designed to work on iPhone.
- Local on-device AI requires WebGPU plus a compatible adapter and sufficient device memory. iPhone support varies by iOS version/device; the app now checks for an actual adapter and explains when it is unavailable.
- Install/download local models while online. Large model downloads can use substantial storage and memory.
- The service worker caches the app shell only. It deliberately does not cache model/CDN downloads.
- Browser storage is local to that browser/origin and is not automatically synchronized with a computer.

APP ICON
The package includes a custom toxic-green Fuggler-style monster icon. Keep app-icon.svg, apple-touch-icon.png, icon-192.png, and icon-512.png in the repository root alongside index.html and manifest.webmanifest. iPhone uses apple-touch-icon.png when added to the Home Screen; supported browsers use the manifest PNG icons.
