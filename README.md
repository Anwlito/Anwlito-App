# Anwlito App Android project

This project packages the supplied Anwlito App website and the included ModsOpti site inside an Android WebView.

## Build an APK

The project includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.

1. Create a GitHub repository and upload the contents of this project.
2. Open the repository's **Actions** tab.
3. Run **Build Anwlito App APK** (or push to the `main` branch).
4. Open the completed workflow run and download the artifact named `Anwlito-App-debug-apk`.
5. Inside it, `app-debug.apk` is the installable debug APK.

The app ID is `com.anwlito.app`, minimum Android version is Android 6.0 (API 23), and the app name is **Anwlito App**.


## Pantallas incluidas
- **Anwlito Socials**: pantalla principal integrada en `app/src/main/assets/site/index.html`, con sus recursos locales.
- **ModsOpti**: integrada en `app/src/main/assets/site/ModsOpti/ModsOpti-main/`. El botón de regreso vuelve a Anwlito Socials mediante una ruta local.
