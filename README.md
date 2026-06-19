# Arrow Slither Escape PWA

Installable Progressive Web App build for GitHub Pages.

## Deploy to GitHub Pages

1. Upload all files in this folder to your GitHub Pages branch/folder.
2. Make sure the main file is named `index.html`.
3. In GitHub: Settings → Pages → Deploy from branch.
4. Open the GitHub Pages URL on Android Chrome or iOS Safari.

Android Chrome will show the in-app Install prompt when the browser fires `beforeinstallprompt`.

iOS Safari cannot trigger installation programmatically. The app shows instructions: tap Share → Add to Home Screen.

The service worker caches the app shell for offline play after the first load.
