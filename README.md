# IOR Naval Watch (Android)

Standalone Android build of IOR Naval Watch. The app ships with maps and a full copy of the data, so it works offline, and fetches the latest `data.json` from this repository whenever it opens.

- `index.html` – the app
- `data.json` – reports, events, vessels, hotspots, economy and EW briefs (updated by the daily scan)
- `icon.png` – app icon
- `debug.keystore` – signing key, so each new build installs over the previous one
- `.github/workflows/build.yml` – builds the APK on every change and publishes it under **Releases**

The repository must stay **public** so the app can download `data.json` without a password.
