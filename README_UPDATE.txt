IRENE MARATHON COACH v2
==========================

WHAT CHANGED
------------
This is a complete rebuild of the first app:
- Runna-inspired mobile layout (without copying Runna branding or proprietary assets).
- Updated starting fitness from the Strava export uploaded 25 Sep 2026.
- Workout breakdowns with warm-up, reps, recoveries and cool-downs.
- Pace ranges for every running component.
- Three-core-run weekly structure.
- Tuesday 3–4 km swim and Wednesday climbing built in.
- 28 Jan–28 Mar 2027 treadmill-only ship block.
- Post-run logging: distance, time, RPE, HR, fatigue and pain/niggles.
- Adaptive reduction of volume/quality after high RPE or pain.
- Editable 3:45 / 3:50 / 4:00 goal.
- Editable 24/25 April 2027 London race day.
- Strava activities.csv import INSIDE the app for future updates.
- Backup/export and restore.
- Keeps the original "marathonLogs" localStorage key, so existing v1 logs are preserved
  when you deploy this over the old app on the same GitHub Pages site.

UPDATED STRAVA SNAPSHOT
-----------------------
From the uploaded 25 Sep 2026 export:
- 40.8 km across 6 runs in the most recent 28-day snapshot.
- 23.36 km in the latest 14-day snapshot.
- Longest recent run: 13.0 km on 19 Sep.
- Recent short runs: 5.01 km on 22 Sep and 5.35 km on 24 Sep.
- Historical activity markers retained in the app for context.

HOW TO UPDATE YOUR EXISTING GITHUB PAGES APP
--------------------------------------------
1. Unzip this package.
2. In your existing GitHub repository, replace:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - icon-192.png
   - icon-512.png
3. Commit the changes to main.
4. GitHub Pages will rebuild automatically.
5. Open the Pages URL in Safari once and refresh.
6. If the old installed iPhone version is still cached:
   - close the app completely from the iPhone app switcher;
   - visit the GitHub Pages URL in Safari and refresh;
   - reopen the Home Screen app.
The service-worker cache version has been bumped, so it should then update.

PRIVACY
-------
Training logs and imported Strava CSV data are processed and stored locally in the
browser. The app does not send them to GitHub or another server.

IMPORTANT TRAINING NOTE
-----------------------
The app is deliberately conservative while running-specific durability is rebuilding.
Easy/long-run pace is guidance only. Conversational effort overrides the number.
Pain that changes running mechanics or worsens during a run is a reason to stop and
seek appropriate clinical advice, not a reason to follow the app harder.
