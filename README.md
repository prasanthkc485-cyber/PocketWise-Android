# PocketWise Android WebView project

This Android Studio project wraps the supplied PocketWise `index.html` in a WebView.

## Build APK
1. Open this folder in Android Studio.
2. Allow Gradle sync (Android SDK Platform 35 and a compatible Android Gradle plugin will be installed if needed).
3. Select **Build > Build APK(s)**.
4. The debug APK is normally at `app/build/outputs/apk/debug/app-debug.apk`.

Application ID: `com.pocketwise.app`  | Version: `2.0`

Notes: This is a WebView packaging of the supplied HTML prototype, not a complete native rewrite. It retains the HTML app's localStorage-based data behavior. A release APK requires signing configuration.
