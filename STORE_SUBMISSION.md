# TweenCraft Adventure — Store Submission Guide

## 📱 App Details (Use these for both stores)

- **App Name:** TweenCraft Adventure
- **Short Description:** A thrilling 9-level platformer with unique worlds and epic music!
- **Full Description:**
  > TweenCraft Adventure is an action-packed mobile platformer featuring 9 beautifully crafted worlds — from the Tutorial Forest to the epic Boss Level! Jump, dodge enemies, collect stars and conquer each unique theme: Ice, Fire, Ocean, Desert, Space, and more. Featuring procedurally generated music, smooth touch controls, and stunning visual effects. Easy to learn, hard to master!

- **Category:** Games > Action / Arcade
- **Content Rating:** Everyone (E) — no violence, no ads, no in-app purchases
- **Version:** 1.0.0
- **Package Name:** com.tweencraft.adventure

## 🏪 AMAZON APPSTORE — Step by Step

1. Go to: https://developer.amazon.com/apps-and-games
2. Sign in (or create free account)
3. Click **"Add a New App"** → Select **Android**
4. Fill in:
   - App title: `TweenCraft Adventure`
   - Category: `Games > Arcade`
   - Content rating: `Everyone`
5. Upload your **APK file** (build using BUILD_INSTRUCTIONS.md)
6. Add screenshots (min 3, size: 1024x500 or 800x480)
7. Add app icon: **512×512 PNG** (transparent background)
8. Submit for review — Amazon approves in **1-3 days** ✅

## 📲 SAMSUNG GALAXY STORE — Step by Step

1. Go to: https://seller.samsungapps.com
2. Create free Samsung seller account
3. Click **"Add New App"**
4. Select **Android APK** → Upload your APK
5. Fill in app info:
   - App name: `TweenCraft Adventure`
   - Category: `Game > Action`
6. Add screenshots + icon (512×512 PNG)
7. Set price: **Free**
8. Submit — Samsung approves in **3-5 days** ✅

## 🔨 BUILD YOUR APK (Required before upload)

See `android/BUILD_INSTRUCTIONS.md` for full steps.

**Quick Summary:**
```bash
cd android
npm install
npm run build        # builds the web assets
npx cap sync android # syncs to Android
npx cap open android # opens Android Studio
# In Android Studio: Build > Generate Signed APK
```

## 🖼️ What You Need Before Submitting
- [ ] Signed APK file (from Android Studio)
- [ ] App icon 512×512 PNG
- [ ] 3-5 screenshots (phone screen recordings)
- [ ] Feature graphic 1024×500 PNG (optional but recommended)

## 🌐 Live Web Version
Play online: https://khana768150-stack.github.io/tweencraft-adventure/
