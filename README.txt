SPARK COMMAND CENTER — GITHUB PAGES SETUP

This folder is a ready-to-publish static website package. To get a permanent HTTPS address and add it to your iPhone Home Screen:

1. Sign in to GitHub or create an account at github.com.
2. Create a new repository named spark-command-center. For easiest setup, set it to Public.
3. Upload all five files from this folder to the repository root: index.html, manifest.json, sw.js, icon-192.png, icon-512.png.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch. Select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish. The address will look like https://YOUR-USERNAME.github.io/spark-command-center/ .
7. Open that published address in Safari on your iPhone. Tap Share > Add to Home Screen > Add.

Notes:
- Replace YOUR-USERNAME with your GitHub username; the actual URL is shown in Settings > Pages.
- The screenshot reader loads Tesseract.js from jsDelivr, so OCR needs an internet connection. Manual entry and the main app may load from cache after the first visit.
- Orders and settings are saved in that browser's local storage on that device. They do not automatically sync to other devices or browsers. Avoid clearing Safari website data if you want to preserve the log; export your order log periodically as a backup.
- This is an independent tracking tool, not affiliated with Walmart/Spark. It cannot monitor or accept Spark offers automatically.
