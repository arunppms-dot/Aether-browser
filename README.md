Aether Browser (Android)
1. Install Android Studio. File > Open > select this folder, let Gradle sync.
2. Run on a phone/emulator, or Build > Build APK(s).
Ad blocking: AdBlocker.kt checks every WebView request (shouldInterceptRequest) against the domain list, then hides ad elements with CSS.
Add domains to AdBlocker.kt, or from the start page > Personalise > Custom block rules.
