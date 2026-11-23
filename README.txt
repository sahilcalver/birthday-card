SANA JAWAD BIRTHDAY GIFT CARD - ANDROID STUDIO PROJECT
======================================================

1. Extract this ZIP file on your laptop.
2. Open Android Studio -> Click "Open" -> Select the extracted "SanaBirthdayCard" folder.
3. Add your audio files into:
   app/src/main/assets/music/
   - birthday_intro.mp3  (Plays immediately when "Open Your Birthday Card" is tapped)
   - song1.mp3, song2.mp3, etc. (Her fixed favorite songs, which play automatically after the intro)
   (You can also edit OPENING_SONG and FIXED_PLAYLIST in app/src/main/assets/index.html to change titles or filenames).
4. In Android Studio, click:
   Build -> Build Bundle(s) / APK(s) -> Build APK(s)
5. Locate the generated APK in app/build/outputs/apk/debug/app-debug.apk and install it!

POEMS: paste your chosen couplets into app/src/main/assets/poems.js (one card per entry, use \n for line breaks).
SYNC FIX: project now uses Gradle 8.5 + AGP 8.2.2 (Gradle 9 is not supported by AGP 8.2.2). In Android Studio set
File > Settings > Build Tools > Gradle > Gradle JDK = "jbr-17" (Embedded JDK) before syncing.
