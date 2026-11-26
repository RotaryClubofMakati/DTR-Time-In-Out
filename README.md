# QR DTR System

Files: `index.html` (app) · `manifest.json` + `sw.js` + `icon-*.png` (phone install) · `Code.gs` (Google Apps Script backend — NOT uploaded to GitHub; paste it into script.google.com).

## 1. Backend (Google Apps Script)
1. Open your Apps Script project, replace the code with `Code.gs`.
2. Change `ADMIN_PIN` and `SCANNER_PIN` at the top.
3. Deploy > Manage deployments > Edit > New version > Deploy (Execute as: Me, Access: Anyone).

## 2. Put the app live on GitHub Pages
1. Create a GitHub repo, upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`.
2. Settings > Pages > Source: Deploy from branch > `main` / root > Save.
3. Your app is at `https://<username>.github.io/<repo>/`.

## 3. Install on phones
Open the link in Chrome (Android) > menu > Install app / Add to Home screen. On iPhone use Safari > Share > Add to Home Screen.
Sign in with the Scanner PIN to scan only, or the Admin PIN for employees, DTR, CSV and printing.
