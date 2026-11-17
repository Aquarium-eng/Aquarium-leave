AQUA LIFE PWA

Files:
- index.html: game interface
- game.js: game logic and local save
- manifest.webmanifest: installable app metadata
- sw.js: offline cache
- icon-192.png / icon-512.png: app icons

How to publish:
1. Upload all files preserving the folder structure to an HTTPS static hosting service.
2. Open the published HTTPS URL in Chrome on Android.
3. Open Chrome menu (⋮) and choose "アプリをインストール" or "ホーム画面に追加".
4. Launch AQUA LIFE from the home screen.

Notes:
- PWA installation requires HTTPS (localhost is also allowed for development).
- Game progress is stored in this browser's local storage. Clearing browser data or switching browsers/devices may erase or not transfer progress.
- Features included: free-swimming fish animation, 24h/50% hunger decay with fish mortality at 0%, main tank decoration sync, food preference, task rewards, gacha, and collection.
