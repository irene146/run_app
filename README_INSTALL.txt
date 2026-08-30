IRENE'S MARATHON COACH — INSTALLATION

What this is
------------
A small private Progressive Web App (PWA) containing your London 2027 training plan.
It stores your training logs locally on your device and adapts upcoming sessions using
simple conservative rules based on completion, RPE and pain/niggle flags.

Important
---------
For iPhone "Add to Home Screen" installation and offline behaviour, the app needs to be
served from an HTTPS website. iOS does not reliably install a downloaded local HTML file
as a full PWA.

Easiest ways to host it
-----------------------
1. GitHub Pages
   - Create a new repository.
   - Upload all files from this folder.
   - Enable Pages in repository Settings > Pages.
   - Open the resulting HTTPS address in Safari on your iPhone.
   - Tap Share > Add to Home Screen > Add.

2. Any static HTTPS host
   - Upload index.html, manifest.webmanifest, service-worker.js and both icon PNGs.
   - Open the HTTPS address in Safari.
   - Tap Share > Add to Home Screen.

Data and privacy
----------------
Your run logs are kept in browser local storage on the device where you use the app.
They are not sent anywhere.
Use Progress > Export backup occasionally so you can restore your history.

Current training assumptions
----------------------------
- Normal week: 3 core runs.
- Tuesday: 3–4 km swim until the ship period.
- Wednesday: climbing until the ship period.
- 28 Jan–28 Mar 2027: treadmill-only block.
- Easy pace is intentionally conservative after your recent running break.
- Pace guidance never overrides pain or an easy conversational effort.
