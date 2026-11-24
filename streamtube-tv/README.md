# StreamTube TV 32-bit build
Standalone Android TV **prototype**, not the official Stream-Tube-Desktop app.
The upstream desktop app uses Rust/GPUI and cannot be packaged as Android without porting.
The source for this experimental Java app is in [source.zip](source.zip).

Build runs on push to `streamtube-tv-32bit`. Download the **APK** from the workflow's artifact section after the workflow completes.
This is a 32-bit-compatible bytecode-only APK (no native ARM64 dependencies), intended for Android TV 7+ testing.

Current alpha: search / trending via public Piped APIs, native VideoView playback, remote control, SponsorBlock sponsor skips.
Piped instances sometimes fail. Video format availability varies. Not device-tested; no original GPUI UI, Google sign-in or downloads.
