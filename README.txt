FIELDATLAS V2 — USGS LIVE MAP + OFFLINE TILE PACKS

NEW: Satellite and topographic maps from USGS The National Map. Select the layer, browse on Wi-Fi, and use Download visible map to save a bounded area at three zoom levels. Offline maps must be saved BEFORE losing signal.

TO UPDATE GITHUB:
1. Extract this ZIP. In your public github.com/ryanmh21/fieldatlas repo, replace index.html and sw.js with the two updated files from this ZIP (and optionally README.txt).
2. Wait for GitHub Pages to deploy, then open the URL on iPhone Safari, refresh online, and fully close/reopen Home Screen app if it still shows V1.
3. Find your hunting location. Choose Satellite or Topo. Zoom to the desired area then tap Download visible map; download several nearby areas if needed.
4. IMPORTANT: test Airplane Mode at home before travel, including relaunch of app. iPhone can clear website storage without notice.

LIMITATIONS:
- USGS aerial imagery may be dated; it is not live satellite video. At very close zoom, imagery may stop being available.
- Offline tiles are saved in browser CacheStorage and may be evicted by iOS. Not reliable enough as sole backcountry navigation system.
- Offline download saves only visible extent at selected zoom plus two higher levels, for current layer; repeat for Topo and Satellite.
- Parcel ownership/lines are NOT automatically populated. Import GeoJSON with verified rights from Texas GIO/county sources.
- No survey precision; landowner names and boundaries may be incomplete/outdated.
- Uses no paid API. Public-domain USGS mapping data service sources: https://www.usgs.gov/faqs/what-are-terms-uselicensing-map-services-and-data-national-map and https://basemap.nationalmap.gov/arcgis/rest/services
- Does not request personal data accounts. Points and tracks remain stored locally on device and should be backed up.
- This build has not been device-tested. Web service availability is controlled by USGS.
