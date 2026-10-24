ZIKR: HOW TO GET YOUR APK (about 5 minutes, free)

1. Make a free account at github.com and click New repository (name it zikr, keep it Private).
2. On the new repo page click "uploading an existing file". Unzip this folder on your computer
   and drag EVERYTHING inside it (www, .github, package.json, capacitor.config.json, .gitignore)
   into the page. Click Commit changes.
   If the .github folder did not upload: click Add file > Create new file, type
   .github/workflows/build-apk.yml as the name, paste the contents of build-apk.yml.txt, commit.
3. Open the Actions tab. A run called "Build APK" starts by itself (about 5-8 minutes).
   If it does not, open Build APK on the left and press Run workflow.
4. When it turns green, open the run and download "zikr-apk" at the bottom (a zip). Unzip it to get app-debug.apk.
5. Send app-debug.apk to your phone, tap it, and allow "Install unknown apps" if Android asks.

Updating later: replace www/index.html in the repo and commit; the APK rebuilds.
Your data is stored inside the app. Use Stats > Download CSV to back up before uninstalling.
