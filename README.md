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
  - Keyboard/mouse (Arrow Keys for pitch/roll, Space for firing, mouse-look camera)
  - Speed (Keys 0-9 or W/S);
  - Missiles (M for opening seeker and then WASD to move locking and M to fire or close seeker)
  - Bomb (B)
  - Flaps (F)
  - Radio (R)
  - AutoPilot (P)
  - Landing Gear (G)
  - Speeds 1-3 and full flaps and gear are required for a landing.
  - Afterburner (V)
  - Flares(for SAM MISSILES) (X)
  - Map (Z)
  - Wingmen; Form/Engage (L)
  - TimeOFDay (T)
  - Camera View (C)
  - Full touch UI for mobile/tablet — virtual stick, throttle slider, and on-screen fire/action buttons (auto-enabled in touch mode)
- Responsive viewport handling for both desktop and mobile play

## Run it
Just open `Skywarrior.html` in a modern browser (Chrome, Safari, or Firefox). No installation, dependencies, or server needed — the entire game, including its 3D engine, is bundled in the file. To use microphone run on terminal or on VS Code
- **To start after running the game press 9, V and then nose down.

## Project Structure
```
Skywarrior.html   # Full game: markup, styles, embedded Three.js engine, and game logic in one file
```
Thank You in part to Anthropic's Claude who helped me a lot in bringing my idea into fruition.
