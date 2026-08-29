# Notes Clone (Android)

Apple Notes-inspired notes app. Kotlin + Jetpack Compose + Room.

## Features
- Notes list with pin, search (animated bottom bar), folders (drawer)
- Note editor: title, body, checklist, image attachments
- Light theme, glass-style cards, list/screen transition animations
- Local storage only (Room DB), no cloud sync

## Run locally (Android Studio)
1. Open this folder in Android Studio (Koala+ recommended).
2. Let Gradle sync (it will download the wrapper automatically first run,
   or run `gradle wrapper` once from a terminal with Gradle installed).
3. Run on emulator/device (minSdk 26).

## Export APK via GitHub
1. Push this repo to GitHub.
2. Go to Actions tab → "Build APK" workflow → it runs automatically on
   push to `main`, or trigger manually via "Run workflow".
3. Download the `notes-clone-debug-apk` artifact when the run finishes.

No signing config is included — this produces a debug APK, installable
directly on a device with "install from unknown sources" enabled.
