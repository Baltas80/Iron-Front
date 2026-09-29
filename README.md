# IRON FRONT

IRON FRONT is a modified build of Mindustry based on **Mindustry v8 Build 160.5**.

## Project status

- Android package: `io.anuke.ironfront`
- Android minimum API: 21
- Android target API: 36
- Engine/runtime base: Mindustry v160.5
- Gameplay systems: upstream implementation retained
- Android startup: verified on an Android 12 emulator and on a physical device
- Build system: Gradle + JDK 17

## Android build

From the repository root:

```bash
./gradlew pack
./gradlew android:assembleRelease -Pbuildversion=160.5 -PversionType=official
```

The APK is produced at:

```
android/build/outputs/apk/release/android-release.apk
```

## Source and license

IRON FRONT is based on Mindustry and remains subject to the GNU General Public License v3.0 and the notices contained in this repository.

This repository contains modifications to the original Mindustry project. The corresponding source is provided in this repository.

See [LICENSE](LICENSE) and [NOTICE-IRON-FRONT.txt](NOTICE-IRON-FRONT.txt).

Original project: https://github.com/Anuken/Mindustry
