# FUTOROW AI Android MVP — UI v1.1

A polished, responsive music-studio interface wrapped in a native Android WebView.

## Included
- Artist, Beatmaker/Producer, DJ and Piano creator modes
- Music blueprint, lyrics, chords, arrangement, mixing and promotion starter tools
- Responsive desktop/mobile navigation and studio dashboard
- Local recent-project history using browser localStorage
- Copy generated plan action

## Important limitations
- This is a preview/MVP. Built-in guidance is demo logic, not real AI generation.
- No Appwrite backend, authentication, cloud sync, audio upload or track analysis is connected yet.
- Saved projects are stored locally on the device/browser only.

## Build APK
1. Open this project folder in Android Studio.
2. Allow Gradle sync (Android Gradle Plugin 8.7.3; compile SDK 35).
3. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Install the generated debug APK from `app/build/outputs/apk/debug/app-debug.apk`.

The GitHub Actions workflow in `.github/workflows/build-apk.yml` can also build the debug APK after the project is pushed to GitHub.
