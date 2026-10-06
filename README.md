# Android Java layout experiment

An Android layout experiment described in the original project notes as using vertical and horizontal layout helpers and a vertical scroll view.

## Repository contents

- Android Gradle Plugin 8.0.2 configuration; Gradle project name: `ShareTwo`.
- Gradle launcher scripts and AndroidX configuration.
- [Recorded layout demo](ScrollViewScreenshot.webm).

## Setup and run

This checkout is incomplete and cannot currently build an Android app: `settings.gradle` includes `:app`, but the app module, Java source, resources, manifest, and Gradle wrapper files under `gradle/wrapper/` are absent.

To run the original project, first restore those files from your own project copy, open the complete project in Android Studio, configure your local Android SDK, sync Gradle, and run the app on an emulator or device. The tracked `local.properties` contains a machine-specific SDK path; replace it locally rather than reusing that path.

## Scope

The recording preserves a demonstration of the layout experiment. The current source snapshot does not let a visitor inspect or verify the layout implementation.
