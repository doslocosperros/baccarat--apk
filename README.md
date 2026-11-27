# Baccarat (offline APK)

Free, play-money Punto Banco baccarat for Android. Fully offline: the app declares no INTERNET permission.

- Game: `app/src/main/assets/index.html` (single file, plain JS)
- Wrapper: `app/src/main/java/com/funfacts/baccarat/MainActivity.java` (WebView)
- Rules: 8-deck shoe, standard third-card rules. Player 1:1, Banker 0.95:1, Tie 8:1, Player/Banker push on tie.

## Build
Needs JDK 17+, Gradle 8.7+ and the Android SDK (platform 34, build-tools 34).

    gradle assembleDebug

APK: `app/build/outputs/apk/debug/app-debug.apk` (debug-signed, for sideloading).
