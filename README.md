# Block Stack

Minimalist block stacking game — single-file HTML5 canvas game wrapped with [Capacitor](https://capacitorjs.com/) for iOS and Android.

## Local development

```bash
npm install
npm run serve   # opens http://localhost:8080
```

Or just open `www/index.html` directly in a browser.

## Mobile build

Requires Xcode (iOS) and/or Android Studio (Android) installed.

```bash
# First time, add platforms
npm run cap:add:ios
npm run cap:add:android

# Generate icons + splash from assets/ (see assets/README.md)
npm run assets:generate

# After any change to www/
npm run cap:sync

# Open in native IDE
npm run cap:open:ios
npm run cap:open:android
```

## Structure

- `www/index.html` — the game
- `capacitor.config.json` — app id, AdMob config
- `ios/`, `android/` — generated native projects (committed)
