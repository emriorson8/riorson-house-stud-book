RIORSON HOUSE STUD BOOK — GITHUB PAGES EDITION

This folder is prepared for free GitHub Pages hosting. It includes the upgraded stud-book HTML plus a web-app manifest and offline service worker.

PUBLISHING (one-time setup):
1. Sign in/create an account at https://github.com/
2. Create a NEW repository. For the simplest free GitHub Pages setup, make it Public. Name it riorson-stud-book.
3. Choose Add file > Upload files and upload ALL files and folders from this package (index.html, manifest.webmanifest, sw.js, icons).
4. Commit the upload.
5. In the repository open Settings > Pages. Under Build and deployment choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub to publish; the Pages URL appears in Settings > Pages. Open that URL in Safari.
7. In Safari tap Share > Add to Home Screen.

UPDATING WITH YOUR FRIEND:
- Keep this original source ZIP as the master.
- When your friend upgrades it, ask them to return the complete updated project (index.html and any changed/new supporting files), preferably as a ZIP.
- Before replacing files, use the stud book's own Backup/Export function and save the backup somewhere safe.
- Upload/replace the updated project files in the SAME GitHub repository and commit. Keep the same Pages address.
- Because the address stays the same, the browser's local IndexedDB database normally remains associated with the same site. Still back up first, as code/database changes can affect compatibility.

IMPORTANT DATA NOTES:
- GitHub Pages hosts the app files; it does NOT store or sync your horse records. Records are stored in the browser on each device.
- Your friend's records and your records remain separate unless you deliberately import/share a data backup.
- Do not open the downloaded HTML file directly from Files after publishing; use the GitHub Pages web address so the installed app has a stable site identity.
- The service worker caches the app shell for repeat/offline loading after the first successful visit. External Google Fonts may still need internet unless already cached.
- Test with a temporary horse first, then export a backup before entering important records.
