ParkSmart — Parking Coach

Files:
- index.html: app interface, lessons and simulator
- manifest.webmanifest: installable web app metadata
- icon.svg: app icon
- sw.js: offline cache/service worker

Install on Android:
1. Upload the contents of this folder to an HTTPS host (for example GitHub Pages).
2. Open the hosted address in Chrome on Android.
3. Choose Install app from the page button or Chrome menu.

Important:
- The app needs to be served over HTTPS (or localhost for testing) for service-worker/PWA installation.
- This ZIP is the complete PWA source, not a compiled native APK.
- For a native APK, open an Android Studio project or package this hosted PWA with a Trusted Web Activity.
