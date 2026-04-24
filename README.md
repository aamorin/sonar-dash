# Sonar Dash

A mobile-first Phaser 3 arcade game for GitHub Pages. Tap to keep the submarine afloat and send sonar ripples through an otherwise black cavern.

## Run Locally

Serve the folder with any static server, then open it in a browser:

```sh
python3 -m http.server 8080
```

## Offline Use

The game is a PWA. After the first successful online visit, the service worker caches the HTML, icons, manifest, service worker, and local Phaser runtime so it can be reopened offline from the same browser or installed home-screen app. A brand-new recipient still needs one online load before offline play works.

## Deploy

Enable GitHub Pages for the repository and serve from the `main` branch root.
