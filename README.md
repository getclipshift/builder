# ClipSHIFT

ClipSHIFT is a clipboard synchronization tool that keeps your clipboard in sync across your Android device and desktop.

**Source repositories:**
- Android: https://codeberg.org/clipshift/android
- Desktop: https://codeberg.org/clipshift/desktop

---

## Installation

Download the latest release from the [Releases page](https://github.com/getclipshift/builder/releases).

> Releases are published as drafts until manually promoted. Once all build artifacts are attached, the maintainer promotes the draft to a public release.

### Android

Make sure you first have the ntfy.sh app installed as ClipSHIFT utilizes it for push notifications. Setup your subscription to the clipshift topic in there, make sure "Broadcast messages" is enabled in the settings, and I suggest you mute the clipshift topic.

Download `clipshift.apk` and install it on your device. You may need to enable "Install from unknown sources" in your device settings.

**Auto-updates with Obtainium:**
Install [Obtainium](https://github.com/ImranR98/Obtainium) and add this repo to track new releases automatically:

[![Get it on Obtainium](https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png)](https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https://github.com/getclipshift/builder)

### macOS (Apple Silicon)

Download `ClipSHIFT_<version>_aarch64.dmg`, open it, and drag ClipSHIFT to your Applications folder.

> **Note:** The app is currently unsigned. On first launch, right-click the app and choose **Open** to bypass Gatekeeper.

<!-- TODO: publish a Homebrew cask once the app is stable -->

### Linux

Download `clip-shift_<version>_amd64.AppImage`, make it executable, and run it:

```bash
chmod +x clip-shift_*.AppImage
./clip-shift_*.AppImage
```

### Windows

Download `ClipSHIFT_<version>_x64-setup.exe` for the installer, or `clipshift-desktop.exe` for a portable standalone executable.

---

## Building from source

See the individual source repositories for build instructions:
- [Android build instructions](https://codeberg.org/clipshift/android)
- [Desktop build instructions](https://codeberg.org/clipshift/desktop)
