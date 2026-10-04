# The Vice Parade Setlist — Web Hosting Package

This folder is ready to deploy as a static HTTPS website / Progressive Web App (PWA).

## Easiest option: Netlify Drop

1. Unzip this package on your computer.
2. Go to Netlify Drop: https://app.netlify.com/drop
3. Drag the **entire `vice-parade-setlist-web-hosting` folder** onto the page.
4. Netlify will give you an HTTPS address such as:
   `https://your-site-name.netlify.app`
5. Open that HTTPS address in **Safari on your iPhone**.
6. Tap **Share**.
7. Tap **Add to Home Screen**.
8. Name it **Vice Setlist** (or keep the suggested name) and tap **Add**.
9. Launch it from the new icon on your Home Screen.

After the first successful load, the app shell is cached for offline use.

## Updating the hosted app later

Upload the contents of a newer hosting package to the same site. The service worker is versioned so the new build can replace the previous cached build.

## Backing up your data

Your song, setlist, show and rehearsal data is stored locally on the device.

Inside the app:
- **••• → Backup Data (JSON)** saves a backup.
- **••• → Restore Backup** restores it.

Back up before clearing Safari data or moving to a new phone.

## Files in this package

- `index.html` — the app
- `manifest.webmanifest` — installable-app metadata
- `sw.js` — offline service worker
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — app icons
- `_headers`, `_redirects` — Netlify deployment helpers
- `.nojekyll`, `404.html` — GitHub Pages compatibility
- `hero-reference.jpg` — design reference only

## Alternative static hosts

The same folder can also be deployed to GitHub Pages, Cloudflare Pages, Vercel, or any HTTPS static host.
