# Neelam Retro Radio — Android APK

This is a **real native Android project** for GitHub Actions. It is NOT a PWA.

The existing Retro Radio HTML UI is packaged inside an Android WebView, so the app installs as an `.apk` while keeping the radio UI and live-stream controls.

## Login
- Login: `Neelam`
- Password: `Neelam143`

## Footer
`Made with ❤️ for Neelam`

## GitHub → APK

1. Create a new GitHub repository.
2. Upload this entire project to the repository.
3. Commit/push to the `main` branch.
4. Open **Actions**.
5. Select **Build Neelam Android APK**.
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run.
8. Under **Artifacts**, download **Neelam-Radio-APK**.
9. Extract `Neelam-Radio.apk` and install it on Android.

The workflow uses GitHub Actions, JDK 17, Gradle 8.9, and Android Gradle Plugin 8.7.3. It creates an installable debug APK, which is signed with the standard debug key.

## App behavior

- Native Android APK
- Portrait mobile layout
- Login screen
- Neelam credentials
- Live internet radio streaming
- Previous / Play / Pause / Stop / Next
- Volume control
- Visualizer
- Retro Windows 98 style
- Footer: Made with ❤️ for Neelam

## Important

The radio stations are external internet streams. The APK requires internet permission and therefore needs an internet connection for live radio playback.
