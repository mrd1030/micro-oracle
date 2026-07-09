# Micro Oracle

**One genuinely useful micro-action, right now.**

## Advanced Features
- Add notes when logging wins
- Weekly summary in Insights
- Charts with Chart.js

## Capacitor Build Instructions

1. Make sure your final web files are in the `www/` folder.
2. Run:
```bash
npm install @capacitor/core @capacitor/cli
npx cap init
npx cap add ios
npx cap add android
npx cap sync
npx cap open ios
npx cap open android
```

Then build and submit to the stores.