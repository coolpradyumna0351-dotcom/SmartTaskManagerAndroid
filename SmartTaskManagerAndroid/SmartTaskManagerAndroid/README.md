# Smart Task Manager - Android WebView Wrapper

This Android project is a minimal wrapper that loads your web-based Task Manager app inside a WebView.

## How to use
1. Deploy the Streamlit app (the demo I prepared) to **Hugging Face Spaces** or **Streamlit Cloud** and copy the public URL.
2. Open `app/src/main/java/com/smarttask/manager/MainActivity.kt` and replace the `WEB_APP_URL` value with your deployed web app URL.
3. Open the project in **Android Studio** (Arctic Fox or newer).
4. Build -> Build Bundle(s) / APK(s) -> Build APK(s).
5. Install the generated APK on your Android device.

## Notes
- The app requires Internet permission.
- This is intentionally minimal (no native storage). All data is stored in the web app backend (Google Sheets) if configured.

## If you want a native app (offline features)
- Let me know and I can prepare a full native Android app (Kotlin) with local SQLite storage and sync features.

