STUDY QUEST - build the real Android app (no browser bar)

This builds a native app with the game stored inside it. It never opens a website,
works offline, and fonts are bundled. GitHub builds it for you for free, in the cloud.

1. Make a free account at github.com and sign in.
2. Tap + (top right), "New repository". Name it study-quest, keep it Private, press Create.
3. Press "uploading an existing file". Unzip this folder first, then upload EVERYTHING inside it,
   including the hidden ".github" folder and the "www" folder. (A computer makes this much easier than a phone.)
   If ".github" will not upload: press Add file > Create new file, type  .github/workflows/build-apk.yml
   as the name, and paste in the text of that file. Then press Commit.
4. Open the Actions tab. "Build Android APK" starts by itself and takes about 5 to 8 minutes.
5. When it shows a green tick, open it. Under Artifacts, download "study-quest-apk".
6. Unzip it. Copy app-debug.apk to your phone and tap it. Allow "install unknown apps" if asked,
   and press "Install anyway" if Play Protect warns (normal for apps not from the Play Store).

If the run shows a red cross, open it, copy the error text, and send it to Claude.
