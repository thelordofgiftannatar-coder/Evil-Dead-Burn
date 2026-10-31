# Officer K (APK build)

1. Create a new GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Open the repo's **Actions** tab, pick **Build APK**, and run it (it also runs on every push).
3. When it finishes, download **officer-k-apk** from the run page and unzip it to get `app-debug.apk`.

To change the app, edit `www/index.html` and push.

Note: the page expects custom native plugins (`LocalMusic`, `MediaSession`, share target) that are not part of this project. Playback, playlists and the Google Drive button work, but lock-screen controls and native folder scanning need those plugins added.
