# Dedicated opening-window Android app

This Android project is intentionally only a native opening window around:

`https://nacworking.netlify.app/`

The website remains hosted on Netlify and is not copied into the APK. The Android activity opens the site in a WebView, preserves normal system bars, keeps the app portrait, and routes `window.print()` to Android's native print service.

No website functionality is recreated natively in Android.
