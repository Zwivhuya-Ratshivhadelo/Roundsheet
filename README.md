# Roundsheets — web app (for GitHub Pages → PWABuilder)

Host these files, then feed the URL to pwabuilder.com to get an installable APK.

## Host on GitHub Pages
1. Create a repo, upload EVERYTHING in this folder to the repo ROOT
   (index.html must sit at the top of the repo, not inside a subfolder).
2. Repo → Settings → Pages → Source: "Deploy from a branch" → main / root → Save.
3. Wait ~1 min. Your URL appears: https://<you>.github.io/<repo>/

## Make the APK
4. Go to pwabuilder.com, paste that URL, Start.
5. Package → Android. Choose the option that BUNDLES the app offline
   (not the URL-only shell) so you can delete the repo after.
6. Download the APK, install on the tablets.

Files: index.html (the app), manifest.json, sw.js (offline), icon-192/512.png.
Your Power Automate upload URL is already baked into index.html.
