# Flappy Maker — Android build project

This project packages the exact supplied `flappy_maker_release_145_cosmetics_page3_fix.love` game as an Android APK using LÖVE 11.5.

## Build on GitHub (recommended)

1. Create a new GitHub repository.
2. Upload everything in this folder, including `game.love` and `.github/workflows/build-android.yml`.
3. Open the repository's **Actions** tab.
4. Select **Build Flappy Maker Android APK**.
5. Choose **Run workflow**.
6. When the workflow finishes, open the run and download the artifact named `flappy-maker-android-apk`.
7. Extract the downloaded artifact and install the APK on Android.

The workflow downloads/builds the LÖVE Android engine during the GitHub build, so the repository does not need to contain the large LÖVE engine source tree.

## Game source

The game is embedded as `game.love`; no gameplay files were changed.

## Technical details

- LÖVE: 11.5
- Android package: `com.brocadegames.flappymaker`
- App name: Flappy Maker
- Game version: 145.0.0
- Version code: 145
