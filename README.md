# Gateway Education App

A modern Android application built to provide an accessible and user-friendly platform for educational purposes.

## Overview

Gateway Education App is a Java-based Android application designed to deliver educational content and resources to users. The app leverages Firebase for real-time data management and storage capabilities.

## Features

- **Real-time Data Synchronization** - Powered by Firebase Realtime Database
- **File Storage** - Cloud-based storage using Firebase Storage
- **User-Friendly Interface** - Built with Material Design components
- **Image Support** - Circle image views for enhanced UI/UX
- **Permission Management** - Integrated Dexter for runtime permissions
- **Responsive Layouts** - ConstraintLayout for flexible design
- **RecyclerView Implementation** - Efficient list and grid rendering

## Tech Stack

### Frontend
- **Language**: Java
- **UI Framework**: Android (API 16+)
- **Design Library**: Material Design (v1.5.0 - v1.6.0)
- **Layout Engine**: ConstraintLayout (v2.1.3)

### Backend & Services
- **Database**: Firebase Realtime Database (v20.0.3)
- **Cloud Storage**: Firebase Storage (v20.0.0)
- **UI Bindings**: FirebaseUI Database (v3.1.0)

### Key Libraries
- **AppCompat**: v1.4.1 (backward compatibility)
- **RecyclerView**: v1.2.1 (list management)
- **CircleImageView**: v3.1.0 (image handling)
- **Dexter**: v6.2.2 (permissions management)
- **AndroidX**: Full AndroidX migration enabled

## Project Structure

```
GatewayEducationApp/
├── app/                           # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/gateway_education_app/   # Java source code
│   │   │   ├── res/               # UI resources (layouts, drawables, strings)
│   │   │   └── AndroidManifest.xml # App configuration
│   │   ├── test/                  # Unit tests
│   │   └── androidTest/           # Instrumented tests
│   ├── build.gradle               # App-level build configuration
│   └── google-services.json       # Firebase configuration
├── build.gradle                   # Project-level build configuration
├── gradle.properties              # Gradle build properties
├── settings.gradle                # Gradle settings and dependencies
└── README.md                      # This file
```

## Requirements

- **Minimum SDK**: API 16 (Android 4.1)
- **Target SDK**: API 31 (Android 12)
- **Build Tools**: Gradle 7.2.1
- **JDK Compatibility**: Java 1.8+

## Setup Instructions

### Prerequisites
- Android Studio (latest version)
- JDK 8 or higher
- Firebase project setup

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ayushtyagi1337/GatewayEducationApp.git
   cd GatewayEducationApp
   ```

2. Open the project in Android Studio

3. Configure Firebase:
   - Download your `google-services.json` file from Firebase Console
   - Place it in the `app/` directory

4. Build and run:
   ```bash
   ./gradlew build
   ```

5. Deploy to emulator or physical device via Android Studio

## Gradle Build System

The project uses **Gradle** as the build system with the following key configurations:

- **minSdk**: 16
- **targetSdk**: 31
- **compileSdk**: 31
- **Version Code**: 1
- **Version Name**: 1.0

### Build Variants
- **Debug**: Development builds with debugging enabled
- **Release**: Production builds with ProGuard optimization

## Testing

The project includes support for:
- **Unit Tests**: Located in `app/src/test/`
- **Instrumented Tests**: Located in `app/src/androidTest/`

Run tests using:
```bash
./gradlew test              # Unit tests
./gradlew connectedTest     # Instrumented tests
```

## Configuration

### Firebase Integration
The app uses `google-services.json` for Firebase configuration. Ensure your Firebase project is properly set up with:
- Realtime Database
- Cloud Storage
- Proper security rules

### ProGuard Rules
Production builds use ProGuard for code obfuscation. Custom rules are defined in `app/proguard-rules.pro`.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bug reports and feature requests.

## License

This project is open source and available under the MIT License.

## Author

**Ayushtyagi1337** - [GitHub Profile](https://github.com/Ayushtyagi1337)

## Commit History

### Recent Commits

| Commit Hash | Message | Author | Date |
|-------------|---------|--------|------|
| `570f77b` | Add comprehensive README documentation | Ayushtyagi1337 | June 7, 2026 at 5:13 AM UTC |
| `ed71c2e` | Education App | Ayush | June 2, 2022 at 6:28 PM UTC |

---

**Last Updated**: June 2026  
**Repository**: [GatewayEducationApp](https://github.com/Ayushtyagi1337/GatewayEducationApp)
