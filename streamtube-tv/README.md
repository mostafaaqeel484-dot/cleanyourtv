# StreamTube TV V0.2 (Android TV 32-bit)
Independent Android TV alpha based on the feature goals of Stream-Tube-Desktop.
Source: [source.zip](source.zip).
**Fixed:** adds Invidious API sources to Piped, retries providers in parallel, on-screen failure diagnostics, manual HTTPS instance settings and YouTube web/app fallback.
Not a direct Rust/GPUI port, no verified device playback. Public hosts sometimes fail.
Runs on Android TV 7+ including 32-bit armeabi-v7a (no native libraries).
Build APK automatically at each push, under GitHub Actions artifacts.
