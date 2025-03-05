
# Dice Roller App

## Overview
A simple Android application that simulates rolling dice with the tap of a button. This project demonstrates basic Android development concepts using Kotlin, including UI elements, event handling, and image resources.

## Features
- Roll virtual dice with randomized results
- Visual dice face representation
- Simple, intuitive user interface
- Support for multiple dice (optional feature)

## Screenshots
![image](https://github.com/user-attachments/assets/f177ff38-5882-46c8-9c5a-0c1b9eaecab8)


## Technologies Used
- Kotlin
- Android SDK
- Gradle
- Android Jetpack components

## Prerequisites
- Android Studio Arctic Fox (2020.3.1) or newer
- Android SDK version 21+
- Gradle 7.0+
- JDK 11

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/yourusername/dice-roller.git
cd dice-roller
```

### Open and Build in Android Studio
1. Open Android Studio
2. Select "Open an existing Android Studio project"
3. Navigate to the cloned repository and click "Open"
4. Wait for the project to sync and build
5. Connect an Android device or use the emulator

### Run the Application
- Click the "Run" button (green triangle) in Android Studio
- Select a deployment target (emulator or connected device)
- The app should install and launch automatically

## How to Use
1. Launch the Dice Roller app
2. The main screen displays a dice with a default face
3. Tap the "Roll" button to generate a random dice face
4. The dice image will update to reflect the random roll

## Project Structure
```
app/
├── src/main/
│   ├── java/com/example/diceroller/
│   │   └── MainActivity.kt       # Main activity with dice rolling logic
│   ├── res/
│   │   ├── drawable/             # Dice face images
│   │   ├── layout/
│   │   │   └── activity_main.xml # Main UI layout
│   │   ├── values/
│   │   │   ├── colors.xml        # Color definitions
│   │   │   ├── strings.xml       # String resources
│   │   │   └── themes.xml        # App theme definitions
│   └── AndroidManifest.xml       # App configuration
└── build.gradle                  # App module build configuration
```

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Learning Resources
- [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course)
- [Kotlin Programming Language](https://kotlinlang.org/docs/home.html)
- [Android Developers Documentation](https://developer.android.com/docs)


## Acknowledgements
- Android Developers documentation and tutorials
- [Material Design](https://material.io/design) for UI inspiration

---
*This app was created as part of the Android Basics in Kotlin course, demonstrating fundamental Android development concepts.*
