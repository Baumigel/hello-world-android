# Hello World Android

A simple Hello World Android application demonstrating the basics of Android development.

## Features

- Displays "Hello World from Android!" message
- Basic Android app structure
- Uses AppCompat library

## Requirements

- Android Studio 2024.2.1+
- Android SDK 34+
- Java 21+
- Minimum SDK: 21 (Android 5.0 Lollipop)
- Target SDK: 34 (Android 14)

## Installation

### From Source

1. Clone the repository:
```bash
git clone https://github.com/Baumigel/hello-world-android.git
cd hello-world-android
```

2. Build the project:
```bash
./gradlew assembleDebug
```

3. Install on device:
```bash
adb install app/build/outputs/apk/debug/app-debug.apk
```

## Usage

1. Install the app on your Android device
2. Launch the app from your app drawer
3. You will see "Hello World from Android!" displayed on the screen

## Project Structure

```
HelloWorld/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/helloworld/
│   │       │   └── MainActivity.java      # Main activity
│   │       ├── res/
│   │       │   ├── layout/
│   │       │   │   └── activity_main.xml  # Layout XML
│   │       │   └── values/
│   │       │       └── strings.xml        # String resources
│   │       └── AndroidManifest.xml        # App manifest
│   └── build.gradle                      # App-level Gradle config
├── build.gradle                          # Project-level Gradle config
└── settings.gradle                       # Gradle settings
```

## Building

### Debug Build

```bash
./gradlew assembleDebug
```

### Release Build

```bash
./gradlew assembleRelease
```

## Running Tests

```bash
./gradlew test
```

## License

This project is open source and available for educational purposes.
