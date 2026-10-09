# TN Election Results 2026 Android App

This Android Studio project wraps the following website in a simple Android WebView app:

https://tnexplorer.com/elections/tn2026/by-polls/results/

## Build an APK

1. Install Android Studio (current stable version) and the Android SDK.
2. Extract this ZIP file.
3. In Android Studio, choose **Open** and select the extracted `TN_Election_Results_App` folder.
4. Allow Gradle sync and install any requested Android SDK platform (API 35).
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. When the build finishes, select **Locate** in the notification. The APK is normally at:
   `app/build/outputs/apk/debug/app-debug.apk`

## App details

- App name: TN Election Results 2026
- Package: `com.tnexplorer.electionresults`
- Minimum Android version: Android 6.0 (API 23)
- Requires an internet connection.
- This is an unofficial WebView wrapper. It displays website content and does not independently verify or generate election results. Website availability and accuracy depend on the source site.
