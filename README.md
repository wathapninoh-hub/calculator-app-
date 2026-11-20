# Madagascar Driving 3D

Prototype mobile 3D driving game built with Godot? No — this first playable prototype uses Three.js in a mobile web page, so it can be tested on Android without installing a game engine.

## Play
Open `index.html` in a modern browser with an internet connection (Three.js is loaded from jsDelivr).

## Controls
- Left / right buttons: steer
- ACCÉLÉRER: accelerate
- FREIN: brake

## Build
GitHub Actions creates a ZIP package on every push. Open the Actions tab and download the `madagascar-driving3d-web` artifact from the latest successful run.

This is an early prototype: simple procedural 3D scenery and a placeholder car made from shapes. It is not yet a high-detail commercial simulator or an Android APK.


## 3D vehicle model

The playable scene now loads the Spectral GT RS game-ready GLB model from its public source repository at runtime. It is dedicated to the public domain under CC0 1.0 Universal. An internet connection is required to fetch the model. If loading fails, the simple built-in placeholder car remains visible.

Source: https://github.com/JaronKBragg7337/spectral-gt-rs
Model file: spectral_gt_rs_game_ready.glb
License: CC0 1.0 Universal
