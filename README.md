# Lyka Profile App — Unit 8 Exercise

**Course:** CC 207B  
**Student:** Lyka R. Lamparero  
**Year & Section:** BSIT 3A  
**Version:** 1.1.0+2

## Project Overview

This project is a Flutter-based personal profile application developed for the CC 207B Unit 8 Exercise. It features a personal biography, an interactive pet with sound effects, a photo gallery, and a media shelf integrated with external APIs and a Content Management System (CMS).

The application is deployed as a web application through GitHub Pages and packaged as an Android release APK.

## Features

- **Profile:** Displays personal information and biography.
- **Interactive Pet:** Includes a pet interaction with a barking sound effect.
- **Photo Gallery:** Displays personal photos with an individual photo viewing screen.
- **Media Shelf:** Integrates book and movie search through external APIs.
- **My Picks:** Allows users to access their selected or saved items.
- **CMS Integration:** Retrieves content from the configured CMS.

## Version Information

| Component | Version |
|---|---|
| Application version | 1.1.0 |
| Build number | 2 |

## Web Deployment

The web application is published through GitHub Pages using GitHub Actions.

**Live Web Application:**  
https://eysikiel.github.io/my-profile/

The deployment workflow builds the Flutter web application in release mode and supplies the required configuration values through GitHub repository secrets and variables.

## Android Release Build

Build the release APK using:

```bash
flutter build apk --release --dart-define-from-file=dart_defines.json
```

Build the debug APK for comparison:

```bash
flutter build apk --debug --dart-define-from-file=dart_defines.json
```

Generated APK files:

```text
build/app/outputs/flutter-apk/app-release.apk
build/app/outputs/flutter-apk/app-debug.apk
```

## Running the Project Locally

Install dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run --dart-define-from-file=dart_defines.json
```

Build the web application:

```bash
flutter build web --release --dart-define-from-file=dart_defines.json
```

## Unit 8 Deployment and Testing

The application was prepared for web and Android release deployment.

## Repository

**GitHub Repository:**  
https://github.com/eysikiel/my-profile

**GitHub Pages:**  
https://eysikiel.github.io/my-profile/

---

*CC 207B — Unit 8 Exercise | BSIT 3A | November 2026*