SRBC Waste Services Driver Assessment PWA

Open index.html for a quick preview.

For GPS, offline installation and Add to Home Screen on iPad, host the folder over HTTPS, open it in Safari, then choose Share > Add to Home Screen.

The prototype includes:
• touch-first assessment workflow
• eligibility and pre-drive checks
• live GPS route recording
• geotagged observations and speed
• editable written report with guidance
• score matrix
• digital signatures
• draft preview
• Print / Save as PDF
• local offline draft storage
• sample assessment data

The logo tile is a placeholder. An approved SRBC logo can be inserted later.


GitHub Pages update notes
-------------------------
This build uses service worker v2 and forces update checks.

After uploading:
1. Make sure GitHub Pages is publishing the branch/folder containing index.html.
2. Open the site once while online.
3. If an older build remains, remove the site from the iPad Home Screen, clear Safari website data for the GitHub Pages domain, then open and add it again.
4. Future builds should change the CACHE name in service-worker.js, for example v3, v4, etc.
