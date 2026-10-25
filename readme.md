# Accord

A local music player for Android with an Apple-inspired design. Supports synced lyrics (LRC/SRT), gapless playback, and third-party equalizers.

A fork of [Accord](https://github.com/v3ndable/Accord) (which, in turn, is a fork of [@v3ndable](https://github.com/v3ndable)), but with minor updates and fixes.

## Screenshots

<p>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Home.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Browse.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Library.jpg" width="220" />
</p>
<p>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Search.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Player.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Lyrics.png" width="220" />
</p>

## Installation

Download the original Accord-APK (no longer maintained) from [GitHub Releases](https://github.com/emylfy/Accord/releases/latest).

## Required Setup

Before building the project, you must create a `package.properties` file in the root directory:

```bash
$ touch package.properties
````

Then add the following content:

```properties
releaseType=SelfBuilt
```

This is required for Gradle to correctly recognize the build type and allow compilation.

## Building

```bash
git clone https://github.com/Lewandowskiy/Accord.git
cd Accord
./gradlew assembleRelease
```

APK will be in `app/build/outputs/apk/release/`.

> <sub><small>Don't forget to sign the release later.</small></sub>

## Credits

Based on a fork of [@v3ndable](https://github.com/v3ndable), which in turn is a fork of [Accord](https://github.com/emylfy/Accord) by [@emylfy](https://github.com/emylfy), which itself is a fork of [Gramophone](https://github.com/AkaneTan/Gramophone) and [AccordLegacy](https://github.com/FoedusProgramme/AccordLegacy).

Original developers: [@AkaneTan](https://github.com/AkaneTan), [@lightsummer233](https://github.com/lightsummer233), [@123Duo3](https://github.com/123Duo3)

Fork maintained by [@Lewandowskiy](https://github.com/Lewandowskiy)

## License
This project remains under the GNU General Public License v3.0.

GPL-3.0 — see [LICENSE](LICENSE) for details.
