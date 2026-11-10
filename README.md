# SOC MENTOR Android PWA

A mobile-first Progressive Web App for daily L1 SOC Analyst learning. Includes home dashboard, 16-week roadmap, a sample practical challenge, daily score logging, skill mastery, JSON backup/restore, and mentor instructions. Records are stored in browser localStorage on the device.

## Install on Android
A PWA must be served from HTTPS (or localhost) to be installable. Easiest free route:
1. Create a GitHub repository and upload all files in this folder.
2. In repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
3. Open the published HTTPS URL in Chrome on your Android phone.
4. Tap the browser menu → **Install app** or **Add to Home screen**.
5. Open SOC MENTOR from the new home-screen icon. After first load, core screens work offline.

Alternative: host the folder on any HTTPS static host. The app does not need a backend.

## Data and limitations
- Learning records are stored only in that browser on that device. Export JSON backups from Profile regularly.
- To use another phone/browser, export then restore the backup.
- No automatic reminders are configured (user asked to decide later).
- This is a learning tracker and sample practice app, not a certified SOC course. Use authorized labs and synthetic data only.
- ChatGPT mentor interaction happens in ChatGPT; use the included mentor instructions and enter your real session results in the app.
