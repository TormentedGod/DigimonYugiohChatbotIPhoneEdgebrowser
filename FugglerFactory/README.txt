FUGGLER FACTORY — COMPLETE GITHUB PAGES PACKAGE

UPLOAD ALL SIX FILES IN THIS FOLDER TO THE ROOT OF YOUR GITHUB REPOSITORY:
- index.html (the app)
- sw.js (offline service worker)
- manifest.webmanifest (install metadata)
- apple-touch-icon.png (iPhone Home Screen icon)
- icon-192.png (PWA icon)
- icon-512.png (high-resolution PWA icon)

The specimen switcher has been moved OUT of the chat viewport and placed in the safe gap below the title plate. It is kept below the iPhone status/notch area and no longer overlays the top system status area. The chat history padding has been reduced so the selector does not waste message space.

PUBLISHING:
1. Extract this ZIP.
2. Upload every listed file to the ROOT of your GitHub repository (not a nested folder).
3. In GitHub: Settings > Pages > Deploy from a branch > select your branch and / (root).
4. Open the HTTPS Pages URL on your iPhone.
5. For the new icon, remove the old Home Screen shortcut and add the site again.
6. If an old version is cached, close the installed web app and reload the site once while online; the service worker cache is versioned and will update.

NOTE: The offline cache includes the app shell and icons. AI model downloads and remote API calls still require their respective network/model availability.
