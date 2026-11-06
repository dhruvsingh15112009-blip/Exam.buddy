# Exam Buddy PWA

This folder contains a ready-to-host Progressive Web App for the Board Exam 2027 countdown.

## Exam dates included
- Physics — 16 February 2027
- Chemistry — 27 February 2027
- English — 5 March 2027
- Maths — 9 March 2027
- Typo — 12 March 2027
- CS — 31 March 2027

The countdown uses the device's local calendar date, so it updates automatically each day. Exam dates and gaps are fixed in `index.html`.

## Important: installation needs an HTTPS website
A PWA cannot be installed from a `content://` local file. Upload the contents of this folder to a static web host that provides HTTPS. Keep `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder together at the same site path.

## Android installation
1. Open the hosted HTTPS address in Chrome.
2. Open Chrome's ⋮ menu.
3. Tap **Install app** or **Add to Home screen** (wording can vary).
4. Confirm **Install**. Exam Buddy will open in its own app window.

The service worker caches the app files for later offline use after the first successful visit.
