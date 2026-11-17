WING HOP - ANDROID PROJECT

This project packages the supplied Wing Hop HTML game as a full-screen Android app.
It includes the existing narrow pole gap, background music, and pole labels:
FAARIS (1st), EERAM (10th), FIZZYY (20th), HAYAAT (50th).

BUILD AN APK
1. Install Android Studio on a computer.
2. Open Android Studio and choose Open, then select this WingHop folder.
3. Allow Gradle sync to finish. Android Studio may ask to install Android SDK 35; accept it.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. When the build completes, click Locate. The APK is normally at:
   app/build/outputs/apk/debug/app-debug.apk
6. Transfer app-debug.apk to your Android phone and open it to install.
   If prompted, allow installation from that file manager/browser.

The APK is not prebuilt in this package; it must be compiled by Android Studio because
this build environment does not include the Android SDK or Gradle build tools.
