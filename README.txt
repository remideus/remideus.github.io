PALLET COUNTER PWA

This folder is ready to host as a Progressive Web App (PWA).

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

IMPORTANT:
A PWA must be served from HTTPS (for example GitHub Pages). Opening index.html directly from Android storage will not install it as a PWA.

After hosting:
1. Open the HTTPS site in Chrome on Android.
2. Chrome menu (⋮) > Add to Home screen / Install app.
3. Launch Pallet Counter from its home-screen icon.
4. The service worker caches the app for offline use after the first successful load.

Inventory records remain stored locally in that browser/app installation. Use Export CSV periodically as a backup.
