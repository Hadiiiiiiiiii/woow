# Graph Studio — Android APK project

This is the complete Android project for the Graph Studio calculator. It includes the HTML app, Android WebView wrapper, launcher icons, Gradle configuration, and a GitHub Actions workflow to build a debug APK.

## Build APK with GitHub Actions

1. Extract this ZIP.
2. Upload the **contents of the `Graph-Studio` folder** to the root of your GitHub repository (not the parent folder).
3. Open the repository's **Actions** tab.
4. Select **Build Calculator APK** and press **Run workflow** (or push a commit to `main`/`master`).
5. When the workflow finishes successfully, open that run and download the artifact named `calculator-graph-studio-apk`.
6. Extract the downloaded artifact ZIP to get `app-debug.apk`.

The app label and Android status/navigation bar backgrounds are set to black / Graph Studio. This is a debug APK project, not a signed release build.
