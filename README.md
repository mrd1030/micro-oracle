# Micro Oracle

**One genuinely useful micro-action, right now.**

## Capacitor Setup (for real native apps)

```bash
# 1. Install Capacitor
npm install @capacitor/core @capacitor/cli

# 2. Initialize
npx cap init "Micro Oracle" "com.mrd1030.microoracle"

# 3. Add platforms
npx cap add ios
npx cap add android

# 4. Copy web assets (copy your built files into www/ folder)
npx cap sync

# 5. Open in Xcode / Android Studio
npx cap open ios
npx cap open android
```

Then build and submit to App Store / Play Store.

## Icons
Real PNG icons should replace the SVG placeholders in the `icons/` folder for production PWA and app stores.