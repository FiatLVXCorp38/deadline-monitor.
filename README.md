# Deadline Monitor — Command Center

A private, mobile-friendly Progressive Web App designed for GitHub Pages.

## Included
- Deadline register with due date/time, category, priority, notes and reminder lead time
- Overdue, due-today, next-seven-days and completed dashboard counts
- Search, category/status filters, complete/reopen/edit/delete
- CSV export and import
- Browser notification permission and reminder checks while the app is open
- Offline shell caching after first successful load
- iPhone Home Screen installation support

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **new public repository** named `deadline-monitor`.
2. Upload all files in this folder to the repository root (not inside another folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your address will look like `https://YOUR-USERNAME.github.io/deadline-monitor/`.

## Add it to iPhone
1. Open the published HTTPS address in Safari.
2. Tap Share → Add to Home Screen.
3. Enable **Open as Web App** if shown, then tap Add.
4. Open it from the new Home Screen icon.

## Important storage and notification limits
- Records are stored in the browser's local storage on that device. They are not automatically synced to another phone or computer.
- Export CSV backups regularly. Clearing Safari website data or changing devices can remove local records.
- Notification permission is requested by tapping the notification icon or Test notification.
- This starter checks reminder times while the app is open/active. A browser cannot guarantee scheduled alerts while the app is fully closed. Reliable closed-app push notifications require a push service and server-side scheduling, which is not included in this free static starter.
- GitHub Pages is static hosting. Do not store sensitive or confidential information in this app; it has no login, encryption-at-rest, or access controls.

## Updating
Replace the files in the repository with the updated versions and let GitHub Pages redeploy.
