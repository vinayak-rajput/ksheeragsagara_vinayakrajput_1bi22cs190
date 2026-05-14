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

## Getting Started

### Prerequisites

- **Android Studio:** Jellyfish or newer recommended.
- **JDK:** 17+ (Project uses Java 21 compatibility).
- **Capacitor CLI:** Installed globally or via `npx`.

### Setup and Build

1. **Clone the project:**
   ```bash
   git clone <your-repository-url>
   ```

2. **Sync with Web Assets:**
   Ensure your web project is built, then sync the assets to Android:
   ```bash
   npx cap sync android
   ```

3. **Open in Android Studio:**
   Open the `android` directory in Android Studio.

4. **Run the App:**
   Select your device/emulator and click the **Run** button, or use the terminal:
   ```bash
   ./gradlew assembleDebug
   ```

## Project Structure

- `app/src/main/java/com/ksheera/sagara/`: Contains the Kotlin source code (`MainActivity.kt`).
- `app/src/main/res/`: Contains Android resource files (icons, layouts, values).
- `app/src/main/assets/public/`: (Generated) Contains the synced web application assets.

## Recent Updates

- **Migrated to Kotlin:** Converted the project from Java to Kotlin.
- **Optimized .gitignore:** Updated to prevent sensitive or unnecessary files from being committed to version control.
- **Java 21 Support:** Configured build scripts for compatibility with modern JVM standards.

---
*Created for the Ksheera Sagara project.*
