# 🎮 TweenCraft Adventure

A TweenCraft-style Android platformer game built with HTML5/Canvas and the Web Audio API.

## 🕹️ Features

- **9 unique levels** — Tutorial → Jungle → Ice → Fire → Ocean → Desert → Space → Underground → Boss
- **Theme-specific mechanics** — varying gravity, friction, and visual effects per level
- **Procedural music system** — background music generated via Web Audio API
- **7 sound effects** — jump, coin, death, level complete, hit, power-up, boss
- **Touch controls** — D-pad + jump button, optimized for mobile
- **Mute toggle** — 🔊/🔇 button in HUD
- **Progress tracking** — stars per level, localStorage save
- **Android-ready** — PWA manifest + Capacitor project for APK build

## 🚀 Play

Open `game/index.html` in any modern browser — no server needed!

## 📱 Build Android APK

See `android/BUILD_INSTRUCTIONS.md` for step-by-step Capacitor + Android Studio instructions.

## 📁 Structure

```
game/
  index.html       ← Full game (self-contained, ~51KB)
  launcher.html    ← Blob URL wrapper for correct MIME serving
android/
  package.json          ← Capacitor dependencies
  capacitor.config.json ← App config (ID, name, webDir)
  www/
    manifest.json  ← PWA manifest
    sw.js          ← Service worker
  BUILD_INSTRUCTIONS.md
```

## 🌍 Levels

| # | Theme      | Special Mechanic           |
|---|------------|----------------------------|
| 1 | Tutorial   | Standard platforming        |
| 2 | Jungle     | Normal gravity              |
| 3 | Ice World  | Low friction (slippery)     |
| 4 | Fire Zone  | High gravity                |
| 5 | Ocean Deep | Slow movement, water feel   |
| 6 | Desert     | Sandstorm visual effect     |
| 7 | Space      | Low gravity (floaty)        |
| 8 | Underground| Dark theme, tight corridors |
| 9 | Boss Level | Lightning effects, hardest  |
