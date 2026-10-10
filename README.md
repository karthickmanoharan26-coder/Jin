# JARVIS Android Starter

A small native Android starter project for Android 8.0+ (minSdk 26). It provides a dark JARVIS-style screen, tap-to-speak speech recognition, text-to-speech, and a few safe starter commands.

## Current limitations
- This is a starter prototype, not the full assistant requested.
- It does **not** implement always-on "Hey Jarvis" wake-word detection.
- It does **not** include a cloud AI backend, screen capture, circle search, floating overlay, or device automation yet.
- Speech recognition availability/language depends on the Android speech service installed on the phone.
- Online search and AI features require internet.

## Build using only your phone
1. Create a GitHub account if you do not have one.
2. In your browser, create a new repository named `JARVIS-Android-Starter`.
3. Upload the contents of this ZIP, preserving folder paths.
4. Open the repository's **Actions** tab and enable Actions if prompted.
5. Select **Build JARVIS APK** and tap **Run workflow** (or push to `main`).
6. When the workflow completes, open its run, scroll to **Artifacts**, and download `JARVIS-debug-apk`.
7. Extract the APK from the downloaded artifact and install it. Android may ask you to allow installs from your browser/files app.

Never put AI API keys in the Android app source. For the AI stage, use a small backend that stores the key securely.

## Project settings
- Package: `com.example.jarvis`
- Minimum SDK: 26 (Android 8)
- Compile SDK: 35
- Target SDK: 28 for this prototype; update target SDK and adapt behavior before public distribution.
