MY ACCOUNT ANDROID PROJECT

Includes the My Account HTML app (with Developer Mode) inside an Android WebView wrapper. The existing HTML app provides the money overview, transactions, dues/advances, future money, money breakdown, settings/data export and backup/restore features.

APP ICON
All launcher icon resources were resized from the exact user-supplied image 1000129387.png. No replacement/generated logo was used.

BUILD AN APK (requires a computer)
1. Install Android Studio.
2. Extract this ZIP and open the project folder in Android Studio.
3. Allow Gradle sync and install Android SDK Platform 35 and the requested build tools.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK should appear at app/build/outputs/apk/debug/app-debug.apk.
6. Transfer that APK to your Android phone and install it. Android may ask you to allow installs from the file manager.

IMPORTANT
This is an Android source project ZIP, not a compiled APK. It has not been compiled or tested in this environment because Android SDK/Gradle build tools are unavailable.

The app loads app/src/main/assets/index.html locally. Financial records are stored in this app's WebView local storage and may be separate from the browser/Netlify website. Export a JSON backup before switching. Developer Mode's password is embedded in client-side code, so it is a basic lock rather than strong security.
