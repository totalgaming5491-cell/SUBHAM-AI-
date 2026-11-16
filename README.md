# SUBHAM AI – Android app (free build)
Gemini-powered. Needs a free API key from https://aistudio.google.com/apikey (the app asks on first message and stores it on the phone only).

## Build the APK for free with GitHub (no installs)
1. Create a free GitHub account and a new repository.
2. Upload ALL files of this folder keeping the same paths (on a PC: drag and drop the unzipped folder contents; on a phone use Add file > Create new file and type the path, e.g. www/index.html).
3. Open the repo > Actions > Build APK > Run workflow (it also runs on every push to main).
4. When it turns green, open the run and download the artifact SUBHAM-AI-apk. Unzip it, install app-debug.apk on your phone (allow "install unknown apps").

## Or with Android Studio
npm install && npx cap add android && npx cap sync android && npx cap open android, then Build > Build APK.
Add RECORD_AUDIO and POST_NOTIFICATIONS permissions to AndroidManifest.xml.
