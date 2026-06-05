TM LGSR App Icon Pack

Upload these files to the SAME GitHub folder as your index.html:

- app-logo.png
- favicon.ico
- icon-180.png
- icon-192.png
- icon-512.png
- manifest.json

Then add these lines inside the <head> of your HTML:

<link rel="manifest" href="manifest.json">
<link rel="icon" href="favicon.ico">
<link rel="apple-touch-icon" href="icon-180.png">
<meta name="theme-color" content="#6a1b9a">

For GitHub Pages:
Make sure the files are in the same folder as index.html unless you change the paths.
