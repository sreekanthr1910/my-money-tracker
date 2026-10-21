MY MONEY TRACKER — ANDROID INSTALL GUIDE

This is an installable Progressive Web App (PWA) project, not a signed APK. It saves data in the browser's local storage on the device and supports CSV export plus JSON backup/restore.

IMPORTANT
- To install as an app, host these files on an HTTPS website. Opening index.html directly from Downloads is not enough for reliable offline/install behavior.
- No account or cloud sync is included. Data stays in that browser/device. Export JSON backups regularly.
- Clearing browser/site data, changing browser, or losing/resetting the phone can lose data if you have no backup.

EASIEST HOSTING OPTION: GITHUB PAGES
1. On a computer or mobile browser, sign in/create a GitHub account.
2. Create a new public repository named my-money-tracker.
3. Upload index.html, manifest.json, sw.js, icon.svg and README.txt from this folder to the repository root.
4. In repository Settings > Pages, choose deploy from branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the HTTPS website.
6. Open the published website in Chrome on Android.
7. Tap Chrome's three-dot menu > Add to home screen (or Install app) > Install/Add.
8. Open My Money Tracker from your home screen.

USING THE APP
- Initial capital is prefilled as ₹25,00,000; change it under Backup if needed.
- Add each expense or income with date, category, description and payment method.
- Use Transfer for movement between your own accounts; it is excluded from expense totals.
- Use Reports for monthly totals and category breakdowns.
- Export CSV to open in Excel or Google Sheets.
- Download full backup (JSON) and keep it somewhere safe. Restore a JSON backup to recover your ledger; restore replaces current entries.

PRIVACY
This app has no analytics, no remote database, and no bank connection. Local browser storage is not encrypted by this app. Use a phone screen lock and keep exported backups private.
