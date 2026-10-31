MY EXPENSE TRACKER — SETUP

This is a personal, offline-first web app. It stores transactions in the browser's local storage on the device; it does not send them to a server.

QUICK TEST
1. Unzip the folder.
2. Open index.html in a desktop or mobile browser to try it.

INSTALL ON YOUR PHONE (recommended)
The app needs to be served from an HTTPS address for the normal Add to Home Screen / install experience and offline caching.
1. Upload the four app files (index.html, manifest.webmanifest, sw.js, icon.svg) to a private repository or a static HTTPS host such as GitHub Pages or Netlify.
2. Open the resulting HTTPS website in your phone's browser.
3. Android/Chrome: menu ⋮ → Install app or Add to Home screen.
   iPhone/Safari: Share → Add to Home Screen.
4. Open it from the new home-screen icon.

IMPORTANT
- Data is stored separately by browser/device. It does not automatically sync between your phone and computer.
- Use Settings → Download backup regularly. Keep the JSON backup somewhere safe.
- Settings → Import backup can restore a JSON backup.
- Choose the display currency in Settings. Default is INR.
- The app does not connect to bank accounts or process payments.
