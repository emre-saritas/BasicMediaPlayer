# BasicMediaPlayer

A simple Android audio player: browse the device's files and play audio with a custom seek bar.

## Features

- File explorer for finding audio files on device storage
- Playback with Android `MediaPlayer`
- Custom seek bar view

## Tech stack

- Java, Android SDK (min 23, target 33)
- Gradle 6.7.1, Android Gradle Plugin 4.2.1
- AndroidX AppCompat, Material, Navigation

## Getting started

Open the project in Android Studio and run the `app` configuration, or build from the command line:

```bash
./gradlew assembleDebug
```

The app asks for storage permission to read audio files.

## Project structure

```
app/src/main/java/com/emresaritas/basicmediaplayer/
├── MainActivity.java          # player screen
├── FileExploreActivity.java   # file browser
├── FilesAdapter.java
├── MediaManager.java          # playback control
├── CustomSeekerView.java
└── AudioFile.java
```
