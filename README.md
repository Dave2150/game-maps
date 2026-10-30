# GAME MAPS V2 – Night City

Cyberpunk/neon styled map prototype using MapLibre GL JS and OpenFreeMap basemap.

## Publish on GitHub Pages
Upload the files in this folder to the root of the `game-maps` repository, replacing the old `index.html` and adding `manifest.webmanifest` and `icon.svg`. Commit to `main`. GitHub Pages should remain configured for `main` / root.

## Data and services
- Basemap: OpenFreeMap (OpenStreetMap data)
- Nearby POIs: OpenStreetMap via the public Overpass API
- Address search: Nominatim
- Map rendering: MapLibre GL JS

These public community services are free to access but are not guaranteed unlimited or production-grade. Respect their usage policies; requests are throttled and only nearby POIs are queried at zoom 12+.

Attribution is displayed by the map. OpenStreetMap data is © OpenStreetMap contributors (ODbL).

## Current scope
Online prototype only. No turn-by-turn routing, traffic, offline map downloads, or CarPlay yet. Browser geolocation requires HTTPS and user permission.
