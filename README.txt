MY DREAM LIFE — INSTALLABLE PWA

Files:
- index.html: the app
- manifest.webmanifest: app name, icon and install settings
- service-worker.js: offline app shell
- icon-192.png and icon-512.png: app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to install and use its service worker.
Opening index.html directly as a file will NOT enable installation/offline mode.

Easiest publishing route:
1. Create a GitHub account if you do not have one.
2. Create a new public repository, e.g. my-dream-life.
3. Upload ALL five app files from this folder to the repository's main/root folder.
4. In the repository, open Settings -> Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to publish the site. Open the HTTPS address it gives you in Chrome on your phone.
7. In Chrome, open the three-dot menu -> Install app (or Add to Home screen).

Your bucket list is currently saved in that browser/device's local storage. It does not automatically sync between phone and PC. Use the app's Backup and Restore buttons to move your list between devices.
