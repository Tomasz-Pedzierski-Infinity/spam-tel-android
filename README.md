# SpamTel Android

Aplikacja do blokowania spamu telefonicznego.

## Budowanie

Repozytorium używa GitHub Actions do automatycznego budowania APK.

### Wymagania dla budowania lokalnego:
- Node.js 18+
- Android SDK

### Budowanie:
```bash
cd spam-tel-android
npm install
npx cap sync android
cd android && ./gradlew assembleDebug
```

## Struktura
- `www/` - frontend (HTML/JS/CSS)
- `android/` - projekt Android
- `.github/workflows/` - CI/CD

## License
MIT