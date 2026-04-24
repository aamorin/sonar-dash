# Sonar Dash

A mobile-first Phaser 3 arcade game for GitHub Pages. Tap to keep the submarine afloat and send sonar ripples through an otherwise black cavern.

## Run Locally

Serve the folder with any static server, then open it in a browser:

```sh
python3 -m http.server 8080
```

## Deploy

Enable GitHub Pages for the repository and serve from the `main` branch root. After GitHub finishes deploying, open:

https://aamorin.github.io/sonar-dash/

## Run on a Phone

Open the GitHub Pages URL on the phone once while online. Rotate the device if you want to play in landscape.

### iPhone / iPad

1. Open `https://aamorin.github.io/sonar-dash/` in Safari.
2. Tap the Share button.
3. Tap **Add to Home Screen**.
4. Keep the name or rename it, then tap **Add**.
5. Launch Sonar Dash from the new home-screen icon.

### Android

1. Open `https://aamorin.github.io/sonar-dash/` in Chrome.
2. Tap the three-dot menu.
3. Tap **Install app** or **Add to Home screen**.
4. Confirm the install.
5. Launch Sonar Dash from the home screen or app drawer.

## Offline Use

The game is a PWA. After the first successful online visit, the service worker caches the HTML, icons, manifest, service worker, and local Phaser runtime so it can be reopened offline from the same browser or installed home-screen app. A brand-new recipient still needs one online load before offline play works.
