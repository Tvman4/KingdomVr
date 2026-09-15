# Kingdom VR

**applicationId:** `com.Tvman.KingdomVr`  
HTML + WebXR game wrapped as an Android app. Signed release APK via `.github/workflows/build.yml`.

## Play
- Push this folder to GitHub. The workflow builds a **signed release** APK (keystore is generated **inside** `build.yml`) and attaches `KingdomVr-signed.apk` to a Release.
- Sideload on Quest.
- App loads the game and **immediately requests VR**.
- **Controllers only.** Grip + swing. No hand tracking.

## Modes
- **Story** (default): long pilgrimage, 12 shards, hundreds of platforms. This is the long mode.
- **Freeplay:** `index.html?mode=free` — small yard, not an hour.

## Local HTML
Open `app/src/main/assets/index.html` in Quest Browser if you want the page without the APK. It still auto-enters VR.
