IRENE MARATHON COACH v3
==========================

NEW IN v3
---------
- Add any past workout from Progress > Workout history > + Add past workout.
- Plan now shows the previous four weeks so recent missed logs can be added directly.
- Change the workout date and type when back-filling a session.
- Attach a Strava workout screenshot from Photos or Files.
- Screenshots are compressed and stored locally in IndexedDB on the device.
- Saved screenshots appear in Workout history and reopen with the workout log.
- Existing v2 logs/settings remain compatible.

SCREENSHOT PRIVACY
------------------
Screenshots stay in the browser on your device. They are not uploaded to GitHub or another server.
The app stores the image as a reference; it does not automatically OCR/read the numbers, so enter distance, time, HR and RPE in the normal fields.

UPDATING GITHUB PAGES
---------------------
Replace index.html, manifest.webmanifest, service-worker.js, icon-192.png and icon-512.png in the existing repo, then commit to main.
If your installed iPhone app still shows the old version, fully close it, open the Pages URL in Safari and refresh once, then reopen the Home Screen app.
