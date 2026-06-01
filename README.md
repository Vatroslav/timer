# 30s Timer

Jednostavan timer od 30 sekundi. PWA - radi u browseru i može se dodati na početni zaslon telefona gdje se ponaša kao app (ikona, fullscreen, radi offline).

## Korištenje

Otvori na telefonu: **https://vatroslav.github.io/timer/**

Da dobiješ ikonu na home screenu:
- **Android (Chrome):** izbornik (⋮) → *Dodaj na početni zaslon*
- **iPhone (Safari):** Share → *Add to Home Screen*

Nakon toga se otvara fullscreen, bez adresne trake, i radi bez interneta.

## Funkcije

- Odbrojavanje 30s s vizualnim prstenom
- Na nuli: zvučni signal + vibracija (Android)
- Ekran ostaje upaljen dok timer radi (Wake Lock)
- Start / Stop / Ponovi na jednom gumbu

## Tehnički

Čisti HTML/CSS/JS, bez buildanja i bez ovisnosti. Hosta se na GitHub Pages iz `main` brancha.

- `index.html` - cijela app (UI + logika)
- `manifest.webmanifest` - PWA manifest
- `sw.js` - service worker za offline rad
- `icon-*.png` - ikone aplikacije
