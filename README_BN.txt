MY WEB TOOLS — iPhone + Laptop PWA
===================================

IMPORTANT HONEST NOTE
This ZIP is the installable web-app project. It can save data locally on each device.
The current build does NOT automatically synchronize between devices yet. To get shared data, you must publish it on HTTPS and configure a cloud database (Firebase/Firestore) with secure rules. The included setup dialog stores the Firebase config/key but a secure cloud-sync backend is not wired into this first build yet. Do not treat entering a config as working sync.

FEATURES
- iPhone-friendly responsive dashboard
- 10 default categories, max 20 items per category
- Add/edit/delete website cards
- Custom icon images and custom background image
- Dark/light mode
- Search, category filtering
- Drag and drop cards across categories and reorder within a category (desktop mouse)
- JSON Backup/Restore
- PWA manifest and app icons

FILES
- index.html, style.css, app.js
- manifest.json
- icon-192.png, icon-512.png

HOW TO PUBLISH (free hosting option: GitHub Pages)
1. Create/sign in to GitHub.
2. Create a new repository, e.g. my-web-tools.
3. Upload all files from this folder to the repository root.
4. Repository Settings -> Pages -> deploy from branch -> main / root.
5. Wait for GitHub Pages to provide an HTTPS URL.

HOW TO ADD TO IPHONE 11
1. Open the HTTPS website URL in Safari (not inside another app's browser).
2. Tap Share.
3. Tap Add to Home Screen.
4. Enable "Open as Web App" if shown, then tap Add.

HOW TO USE ON LAPTOP
Open the published HTTPS URL in Chrome. The same URL opens the dashboard, but data remains separate on each device until real cloud sync is implemented.

HOW TO KEEP DATA SAFE
Use Backup on each device and save the JSON file somewhere safe. Before Restore, export a backup first.
