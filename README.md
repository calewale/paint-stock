# Paint Stock — phone-ready PWA

This folder contains the installable web-app version of Paint Stock.

## What was added
- Browser-native Excel export
- JSON backup
- JSON restore
- PWA manifest
- Service worker/offline app shell
- Android-friendly standalone display
- Existing stock/shop/archive data model retained

## Important
The app still stores live inventory in the browser's localStorage on the device.
Use **Backup** regularly. The JSON backup is the portable source of truth.

## Install on Android
The files need to be served from an HTTPS web address. Once hosted:
1. Open the Paint Stock page in Chrome on the Android phone.
2. Use Chrome's menu and choose **Install app** / **Add to Home screen**.
3. Launch Paint Stock from the new icon.

A later version can move the data layer to cloud sync if you want the same inventory on multiple devices.
