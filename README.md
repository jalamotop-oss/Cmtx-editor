# CMTX Editor (Android)

CMTX Editor is an Android wrapper for the **CMTX Esword Editor**, packaged as a WebView app with native file picker support.

## Features
- Runs fully offline.
- Opens `.cmtx` or `.xml` files via Android's file picker.
- Exports commentary files with "Save As" support.

## Build
This project can be built with [Codemagic](https://codemagic.io) using the included `codemagic.yaml`.

Local build (if using Android Studio or CLI):
```bash
./gradlew assembleDebug
```
The APK will be in `app/build/outputs/apk/debug/`.
