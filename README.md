# 30s Timer

A simple 30-second timer. It's a PWA - it runs in the browser and can be added to your phone's home screen, where it behaves like an app (icon, fullscreen, works offline).

## Usage

Open on your phone: **https://vatroslav.github.io/timer/**

To get a home-screen icon:
- **Android (Chrome):** menu (⋮) → *Add to Home screen*
- **iPhone (Safari):** Share → *Add to Home Screen*

After that it opens fullscreen, without an address bar, and works without an internet connection.

## Features

- 30s countdown with a visual progress ring
- At zero: audible beep + vibration (Android)
- Screen stays awake while the timer runs (Wake Lock)
- Single button: Start / Stop

## Technical

Plain HTML/CSS/JS, no build step and no dependencies. Hosted on GitHub Pages from the `main` branch.

- `index.html` - the whole app (UI + logic)
- `manifest.webmanifest` - PWA manifest
- `sw.js` - service worker for offline support
- `icon-*.png` - app icons
