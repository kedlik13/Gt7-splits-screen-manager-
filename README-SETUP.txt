GT7 RACE NIGHT CHAMPIONSHIP MANAGER
===================================

PACKAGE CONTENTS
- index.html       Main app
- manifest.json    Home Screen app settings
- sw.js            Offline service worker
- icon-192.png     App icon
- icon-512.png     App icon

WHAT'S INCLUDED
- Local/offline saving on this device
- Standard and Split Screen race formats
- Up to 4 registered drivers (rename and delete from Drivers)
- 3, 5 or 10 race championships
- Standard lap range: 1-6 laps
- Endurance lap range: 1-15 laps
- Separate Generate Track and Generate Laps controls
- Manual lap slider starts at 1 lap on every track
- No repeated tracks within a championship
- Weather, time of day and car class generation
- Finishing positions, car used, winner's total race time and other drivers' time gaps
- Championship points, standings, statistics and race history
- Export and import JSON backups
- Offline use after the first successful load

INSTALL / UPDATE ON GITHUB PAGES
1. Open your GitHub repository in Safari or a computer browser.
2. Open the repository's main (root) folder.
3. Upload and replace the files in this ZIP: index.html, manifest.json, sw.js,
   icon-192.png and icon-512.png. Keep your existing .github/workflows folder.
4. Commit the changes to the main branch.
5. Wait for the GitHub Actions Pages deployment to finish with a green tick.
6. Open your GitHub Pages address in Safari while online.
7. If the old app is already on your Home Screen, close it completely, open the
   website in Safari, refresh it, then launch the Home Screen app again.

IMPORTANT
- Championship data is stored locally in the browser on each device. It does
  not automatically transfer to another phone.
- Use History > Export Backup regularly to save a JSON backup. Use Import Backup
  to restore it on this or another device.
- The first visit needs an internet connection so Safari can download the app
  files. After that, the service worker caches the app for offline use.
- Do not delete your existing GitHub Pages workflow file.


OPENING THE APP ON IPHONE
- Do not open index.html from the iPhone Files preview to test the app.
  Files preview is not a reliable way to run a JavaScript web app.
- After uploading the files and the Pages deployment is green, open the
  GitHub Pages website address in Safari.
- From Safari, use Share > Add to Home Screen if you want an app icon.
