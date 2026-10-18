RUMI MILK TRACKER — GITHUB PAGES PACKAGE

This package contains APP CODE ONLY. It does not contain pumping history or personal records.

PUBLISH FOR FREE USING GITHUB PAGES
1. Create a PUBLIC GitHub repository named rumi-milk-tracker. On GitHub Free, Pages requires a public repository.
2. Extract this ZIP on your device.
3. Upload the CONTENTS of the extracted folder to the ROOT of the repository (not the ZIP itself). Ensure index.html is at the repository root.
4. Do NOT upload rumi-pumping-history-private.json, CSV exports, or any backup containing pumping records.
5. In the repository, open Settings > Pages.
6. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
7. Wait for GitHub Pages to publish and open the generated HTTPS address.
8. On iPhone, open the address in Safari and choose Share > Add to Home Screen.
9. Open Data & backup in the app and import the private JSON backup directly from Files.

PRIVACY NOTES
- Repository and published app code are public. Do not put personal records or backup files in this repository.
- The app stores pumping records in localStorage in the browser on the device. This app has no app server, analytics, or account system and does not transmit pumping records to the hosting provider.
- GitHub may log ordinary website request metadata such as IP addresses.
- Anyone with the website URL can open the app code. This is not access-controlled private hosting.
- Browser storage can be lost if site data is cleared or the app origin changes. Export JSON backups regularly and store them somewhere you control.
- This is a personal tracker, not encrypted medical-record storage.

DATA MIGRATION
Import the private JSON history file separately after opening the hosted app. Check the session count and latest entries, then export a fresh backup. The history file must never be committed to this public repository.
