# App assets

Drop these source files here and `@capacitor/assets` generates every required iOS/Android icon and splash size.

| File | Size | Purpose |
|---|---|---|
| `icon.png` | 1024×1024 | App icon (required) |
| `icon-foreground.png` | 1024×1024 | Android adaptive icon foreground (optional) |
| `icon-background.png` | 1024×1024 | Android adaptive icon background (optional) |
| `splash.png` | 2732×2732 | Splash screen, art centered (optional) |
| `splash-dark.png` | 2732×2732 | Dark mode splash (optional) |

After adding the files, run:

```bash
npx @capacitor/assets generate
```

This populates `ios/App/App/Assets.xcassets/` and `android/app/src/main/res/`.
