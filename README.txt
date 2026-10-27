BUILDMASTER ANDROID STUDIO PROJECT
==================================
This is Android source code, not a compiled APK.

Build an APK:
1. Install Android Studio on a computer and allow it to install a compatible Android SDK.
2. Open this entire android-studio-project folder in Android Studio.
3. Wait for Gradle sync to complete. If prompted, install the SDK platform/build tools requested by the project.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the APK location (usually app/build/outputs/apk/debug/app-debug.apk).
6. Transfer the APK to your Android phone and install it. Android may ask permission to install apps from that source.

The project packages the app locally in a WebView and uses browser local storage. It has no cloud sync, login, online database, or automated updates. Keep backups. Before commercial/public distribution, test carefully and create a signed release build.
