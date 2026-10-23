# AI Agent Worker — Android APK project

This repository is being prepared for the **mobile-first Android app**. The original Kotlin/Jetpack Compose source ZIP still needs to be imported into the repository before a real APK can be built.

## Current status
- Target: Android phone APK (not desktop-first)
- Expected stack: Kotlin + Jetpack Compose + Gradle
- Original app screens in the provided archive include Overview, AI Generator, YouTube Live Studio, Video Studio, Google Drive, Music Library, and Content Scheduler.
- **Do not treat the APK as built or the source as uploaded yet.** The repository currently does not contain the complete original Android project.

## Import the source
Extract the original Android project ZIP so the repository root contains `settings.gradle.kts`, `app/build.gradle.kts`, and `app/src/`. Commit and push those files to `main`.

## Build an APK
Once the Android project source is present, run the GitHub Actions workflow named **Build Android APK**. A successful run will upload the debug APK as a workflow artifact. This workflow cannot succeed until the Gradle project files are in the repository.

## Important
Keep API keys and service credentials in GitHub/Vercel secrets or secure app configuration; never commit credentials into source control.
