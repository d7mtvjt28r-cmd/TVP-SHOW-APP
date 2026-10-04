THE VICE PARADE — SETLIST V12 PWA

V12 turns the prototype into an installable/offline-ready Progressive Web App.

WHAT CHANGED
- Same real-band hero image is used everywhere, brightened with the colourful live-stage lighting direction.
- Installable app metadata and app icons.
- Offline app shell via service worker.
- IndexedDB durable storage, with localStorage fallback.
- Automatic migration of existing browser data from earlier prototypes.
- JSON Backup and Restore.
- Storage-status screen and persistent-storage request where supported.
- Install App command in the app menu.

IMPORTANT FOR IPHONE/IPAD
A PWA cannot be installed from a downloaded file:// URL. The folder must first be hosted over HTTPS.
Once hosted:
1. Open index.html in Safari.
2. Tap Share.
3. Choose “Add to Home Screen”.
4. Launch it from the new home-screen icon.

TESTING
The index.html file will still open as a normal prototype from the ZIP, but offline installation and
the service worker activate only when the files are served from HTTPS (or localhost during development).

DATA
Your song/setlist/show/rehearsal data stays on the device. Use “Backup Data (JSON)” before switching
devices or clearing Safari/browser data.


V12.1 FIX
- Replaced the stretched-looking composite hero with a single-photo wide crop.
- Tuned hero positioning so the band and stage lights sit more naturally across the app.


V12.3 FIX
- Reframed the hero much lower so the three members remain visible in the banner.


V12.4 FIX
- Moved the hero logo to the upper-right and reduced its size so it no longer covers Jean.
