# Iraq Maps — Flutter starter

Package ID: `com.mymap.iraq`

## Features
- Arabic RTL interface.
- Online OpenStreetMap map.
- GPS location permission and current-location button.
- Place search through Nominatim.
- Route request from current GPS location to a searched destination through OSRM.
- GitHub Actions workflow for building a release APK.

## Build APK from your phone
1. Extract `IraqMaps.zip`.
2. Create a GitHub repository named `IraqMaps`.
3. Upload the contents of this folder to the repository root, including `.github/workflows/build-apk.yml`.
4. Use the `main` branch.
5. Open the repository's Actions tab and enable Actions if requested.
6. Run `Build Iraq Maps APK` with **Run workflow** (or push a commit).
7. Open the completed run and download the `iraq-maps-apk` artifact.
8. Extract the artifact and install `app-release.apk` on your Android phone.

## Limitations
This is an online map app, not an offline map package. Tiles, place search, and route calculations need internet. Public Nominatim and OSRM services can be limited or unavailable; use them responsibly and review their policies before production use. Route duration is estimated and may not reflect live traffic. OpenStreetMap attribution is displayed and must remain visible. This ZIP has not itself built or tested an APK; GitHub Actions must succeed first.
