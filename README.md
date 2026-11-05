# 🍎 Orchard Catch

### Catch the fruit. Keep the rhythm. Beat your best.

**Orchard Catch** is a landscape arcade game for Android. Move your basket from side to side, catch the fruit falling through a peaceful orchard, and see how long you can keep up as the pace gradually increases.

It started as a simple idea: a small, relaxing game that is easy to pick up, satisfying to play, and polished enough to feel like its own little world.

**Made by [TechVixx](https://github.com/TechVixx), with help from AI tools.**

---

## 🎮 The game

- Catch falling fruit with a horizontally controlled basket.
- Earn points for each successful catch.
- Keep your three lives for as long as possible.
- React as the spawn rate and falling speed increase.
- Try to beat your saved high score.

## ✨ Features

- **Landscape-first gameplay** designed for horizontal Android screens.
- **Progressive difficulty** that builds as an active run continues.
- **Multiple fruit types** with individual point values.
- **Score and persistent best score** saved locally on the device.
- **Pause, resume, restart, and game-over flow.**
- **Music and sound effects** bundled with the app.
- **Settings** for music, sound effects, and haptic feedback.
- **Offline-first gameplay** with no account or cloud save required.
- **Custom orchard visuals and UI** built for the game's own identity.

## 🧰 Built with

- Kotlin
- Jetpack Compose
- Android SDK
- Gradle Kotlin DSL
- Android `SharedPreferences` for local game settings and records
- Android audio APIs for background music and sound effects

## 📱 Run it in Android Studio

1. Download or clone this repository.
2. Open the project root in Android Studio (the folder containing `settings.gradle.kts`).
3. Use Android Studio's Gradle sync, then select an emulator or connected device and press **Run**.

**Requirements:** Android Studio with a compatible Android SDK and JDK 17 or newer.

### Build a debug APK

Run the `:app:assembleDebug` Gradle task from Android Studio's Gradle tool window.

**Wrapper note:** The original AI Studio export did not include `gradlew`, `gradlew.bat`, or `gradle-wrapper.jar`. If you want to build from a terminal using the wrapper, install a compatible Gradle version and generate the wrapper from the project root:

```bash
gradle wrapper --gradle-version 9.3.1
```

Then use:

**Windows**
```bat
gradlew.bat assembleDebug
```

**macOS / Linux**
```bash
./gradlew assembleDebug
```

The APK is normally generated at:

```text
app/build/outputs/apk/debug/app-debug.apk
```

## 🔌 Offline by design

The core game, artwork, music, sound effects, settings, and high-score storage are bundled or handled locally. You do not need an account, server, or cloud save to play.

Gradle may need an internet connection the first time it downloads Android build dependencies. That is a development/build-time requirement, not an in-game requirement.

## 🤖 A note on AI assistance

AI tools helped during development with code generation, debugging, problem-solving, and design exploration. The project was then iterated on and assembled into the Android game by **TechVixx**.

AI was part of the development process, and it deserves an honest mention. The goal was to use it as a tool to help bring the game idea to life—not to hide how the project was made.

## 👨‍💻 Developer

**TechVixx**  
GitHub: [@TechVixx](https://github.com/TechVixx)

---

Thanks for stopping by. Hope you enjoy a round of Orchard Catch! 🍊
