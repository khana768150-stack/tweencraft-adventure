# TweenCraft Adventure - APK Build Guide

## Requirements (install these first)
- Node.js 18+ → https://nodejs.org
- Android Studio → https://developer.android.com/studio
- Java JDK 17 → bundled with Android Studio

---

## Step 1 — Install dependencies
```bash
npm install
npm install @capacitor/android
```

## Step 2 — Add Android platform
```bash
npx cap add android
```

## Step 3 — Sync web files into Android
```bash
npx cap sync android
```

## Step 4 — Open in Android Studio
```bash
npx cap open android
```

## Step 5 — Build APK in Android Studio
1. Android Studio opens → wait for Gradle sync
2. Menu: **Build → Build Bundle(s)/APK(s) → Build APK(s)**
3. APK mil jayegi: `android/app/build/outputs/apk/debug/app-debug.apk`

---

## Quick Install on Android Phone (without Play Store)
1. Phone mein **Settings → Security → Unknown Sources** ON karo
2. APK file phone pe bhejo (USB / WhatsApp / Email)
3. Open karo → Install karo → Done! 🎮

---

## Release APK (signed, Play Store ke liye)
- Android Studio → **Build → Generate Signed Bundle/APK**
- Keystore create karo → Sign karo → Upload to Play Console

---

## Package Info
- App ID: com.tweencraft.adventure
- Version: 1.0.0
- Min SDK: Android 5.0 (API 21)
- Target SDK: Android 14 (API 34)
