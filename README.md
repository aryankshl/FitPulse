# FitPulse - Workout App

FitPulse is a fitness app designed to help users stay active and healthy with quick, guided workouts. Whether you're at home, at the gym, or traveling, FitPulse gives you access to exercises that can fit into any busy schedule.

## Features
- **7-Minute Full-Body Workouts**: Quick, high-intensity exercises to boost metabolism and increase fitness in a short time.
- **Exercise Tracking**: Track your completed workouts and monitor your progress over time.
- **Customizable Workouts**: Choose your own exercises or follow pre-designed routines.
- **Friendly User Interface**: Easy to navigate, with clear exercise instructions and timers.
- **Pre-built APK for Testing**: Download and test the app using the debug APK provided.
- **Lightweight and Fast**: Optimized for smooth performance on most Android devices.

## Installation

To install and run the app on your Android device:

1. Clone the repository:
   ```bash
   git clone https://github.com/aryankshl/FitPulse.git
   ```
2. Navigate to the project directory:
   ```bash
   cd FitPulse
   ```
3. Open the project in Android Studio.
4. Build the project and run it on an Android emulator or a physical device.
5. Alternatively, download the **app-debug.apk** file from the repository and install it directly on your device.

## Folder Structure

```
FitPulse/
│
├── .idea/                  # Project configuration files for Android Studio
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/fitpulse/       # Source code (MainActivity, other activities, and classes)
│   │   └───└──  res/                             # Resources (layouts, drawables, strings, etc.)
│   └── build.gradle         # Build configurations for the app module
│
├── build.gradle             # Top-level build file
├── gradle/
│   └── wrapper/             # Gradle wrapper configuration files
├── gradlew                  # Gradle wrapper script for Unix-based systems
├── gradlew.bat              # Gradle wrapper script for Windows
├── settings.gradle          # Settings for the Gradle project
└── app-debug.apk            # Pre-built APK for debugging and testing
```
