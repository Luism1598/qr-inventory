QR INVENTORY APP - VERSION 1

Files:
- index.html: the working app
- manifest.json: installable web-app metadata

Features:
- Live QR scanning using the browser BarcodeDetector API when supported
- Manual QR-value fallback
- Parses K, P, Q, 9D, 1T, 1V, and 1P fields
- Manual Location and Notes
- Saves scan history on the device
- CSV export that opens in Excel

IMPORTANT:
Camera access normally requires HTTPS (or localhost). Opening index.html directly as a file may not allow camera access.
For the easiest phone test, upload these files to a simple HTTPS host such as GitHub Pages or another static HTTPS host.

QR example:
K108575#P1021-0150#Q305#9D2329#1T2329#1VYAGEO#1P1021-0150

The app currently uses the browser's built-in QR detector. If a target phone/browser does not support BarcodeDetector, use the manual field or add a bundled QR decoding library in Version 2.
