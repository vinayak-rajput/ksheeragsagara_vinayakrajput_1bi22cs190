# Ksheera Sagara - Android App

This is the Android native project for **Ksheera Sagara**, built using [Capacitor](https://capacitorjs.com/) and [Kotlin](https://kotlinlang.org/).

## Project Details

- **App Name:** Ksheera Sagara
- **Package Name:** `com.ksheera.sagara`
- **Language:** Kotlin
- **Platform:** Android (Capacitor)

## Features

- **Capacitor Integration:** Bridges web content into a native Android container.
- **Kotlin-First:** Fully migrated to Kotlin for modern Android development.
- **Splash Screen:** Uses `androidx.core:core-splashscreen` for a modern launch experience.
- **Custom App Icon:** Uses a theme-specific icon (`app.png`) configured for the launcher.

## Getting Started

### Prerequisites

- **Android Studio:** Ladybug or newer recommended.
- **Node.js & npm:** Required for Capacitor dependencies.
- **JDK:** 21+ (Project uses Java 21 compatibility).
- **Capacitor CLI:** Installed globally or via `npx`.

### Setup and Build

1. **Clone the project:**
   ```bash
   git clone <your-repository-url>
   cd KsheeragSagara_VinayakRajput_1BI22CS190
   ```

2. **Install Dependencies:**
   Install the required Capacitor and Android libraries:
   ```bash
   npm install
   ```

3. **Sync with Web Assets:**
   Ensure your web project is built, then sync the assets to Android:
   ```bash
   npx cap sync android
   ```

4. **Open in Android Studio:**
   Open the root directory in Android Studio.

5. **Build APK:**
   You can generate the debug APK using:
   ```bash
   ./gradlew assembleDebug
   ```
   The APK will be located at `app/build/outputs/apk/debug/app-debug.apk`.

## Project Structure

- `app/src/main/java/com/ksheera/sagara/`: Contains the Kotlin source code (`MainActivity.kt`).
- `app/src/main/res/`: Contains Android resource files (icons, layouts, values).
- `app/src/main/res/drawable/app.png`: The application launcher icon.
- `package.json`: Defines Capacitor and project dependencies.
- `capacitor.config.ts`: Capacitor configuration file.

## Recent Updates

- **Fixed Build Scripts:** Resolved issues with missing `cordova.variables.gradle` and corrected module paths.
- **Custom App Icon:** Integrated `app.png` as the official app launcher icon.
- **Dependency Management:** Added `package.json` to correctly manage Capacitor Android platforms.
- **Git Optimization:** Cleaned up `node_modules` from version control and updated `.gitignore`.
- **Migrated to Kotlin:** Converted the project from Java to Kotlin for modern development standards.

---
*Created for the Ksheera Sagara project.*
