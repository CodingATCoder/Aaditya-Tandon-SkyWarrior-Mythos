# Skywarrior — MYTHOS: War for the Ruined World

A self-contained, single-file HTML5 3D flight combat game built on Three.js. Everything — markup, styles, game logic, and the embedded Three.js engine — lives in one `Skywarrior.html` file, so it runs straight in a browser with no build step, bundler, or server required.

## What it is
You pilot a fighter aircraft over a war-torn 3D landscape, engaging enemy aircraft with cannons and missiles while managing fuel, ammo, and mission objectives. The game tracks radar contacts, missile locks, scoreboards, and level progression, and includes full takeoff/landing mechanics at friendly bases and runways.

## Features
- **3D flight model** rendered with an embedded Three.js engine — full aircraft movement, camera, and terrain rendering
- **Combat systems**: cannon fire, lock-on missiles, enemy AI aircraft and bullets, damage/health tracking
- **Mission structure**: objectives, mission guidance, scoring, and level progression through multiple waves/levels
- **Resource management**: fuel depots and fuel warnings, ammo tracking
- **Radar & targeting**: target selection, target influence/bright indicators, missile target tracking
- **Base operations**: takeoff and landing at runways/bases
- **Dual control schemes**:
  - Keyboard/mouse (WASD for pitch/roll, Space for firing, mouse-look camera)
  - Full touch UI for mobile/tablet — virtual stick, throttle slider, and on-screen fire/action buttons (auto-enabled in touch mode)
- Responsive viewport handling for both desktop and mobile play

## Run it
Just open `Skywarrior.html` in a modern browser (Chrome, Safari, or Firefox). No installation, dependencies, or server needed — the entire game, including its 3D engine, is bundled in the file.

## Project Structure
```
Skywarrior.html   # Full game: markup, styles, embedded Three.js engine, and game logic in one file
```
