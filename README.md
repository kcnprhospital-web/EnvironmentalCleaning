# KCPH Environmental Cleaning Monitoring

Upload everything in this folder to the root of a GitHub repository and enable GitHub Pages.
Keep the folder structure exactly as it is:

```
index.html
manifest.json
sw.js
favicon.ico
icons/
  icon-192.png
  icon-512.png
  icon-maskable-192.png
  icon-maskable-512.png
  apple-touch-icon.png
  favicon-32.png
  favicon-16.png
```

`Code.gs.txt` is the Google Apps Script backend. It does not go to GitHub; it lives in the Apps Script editor.

After you update index.html later, change `kcph-ec-v1` in sw.js to `kcph-ec-v2` (v3, ...) so phones fetch the new version.
