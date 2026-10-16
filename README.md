# Save poa
Static, installable money tracker. All files sit in one flat folder (no sub-folders), so they can be uploaded from a phone.

Files: index.html, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png, icon-maskable-512.png

index.html must be at the top level of whatever you upload. The app itself works from index.html alone; the other files add install and offline support.
To ship an update, change `CACHE` in sw.js (for example `save-poa-v5`).
