FIELDATLAS V1 — FREE OFFLINE-FIRST HUNTING MAP

WHAT WORKS NOW:
- Offline-first app shell after first successful HTTPS installation
- Pan/zoom coordinate canvas; latitude/longitude jump; GPS positioning
- Save/delete stands, feeders, trail cameras, buck sightings and other markers
- GPS tracks while app stays active in foreground
- Distance measuring, saved home point
- Import WGS84 GeoJSON parcel polygons/roads/trails and tap parcels to inspect attributes
- Import georeferenced PNG/JPEG imagery in current session (NOT persistent)
- Export and restore JSON backups
- No accounts, subscriptions, ads, paid APIs, trackers, or external network map services

IMPORTANT LIMITATIONS:
- The background is a coordinate reference grid, NOT a preloaded aerial/topographic map. Actual map data must be sourced and imported legally.
- The app currently saves metadata and GeoJSON in localStorage, which is capacity-limited and can be cleared by iOS. Image overlay is session-only and must be reimported on restart.
- iOS PWA background tracking is not reliable if locked or app is suspended.
- In Safari opened as file://, service workers and geolocation may be unavailable. A secure HTTPS host is needed for a proper iPhone PWA installation. Free hosting providers exist, but their future terms/limits cannot be guaranteed.
- The map is not a survey and not a substitute for landowner permission or safe navigation.
- Do NOT bulk-download OpenStreetMap public tiles for offline use; this violates that service's policy.
- USGS National Map generally offers public domain data, but inspect metadata because some individual topo products contain copyrighted third-party data.
- Texas GIO parcel downloads may be available; verify terms and data validity per dataset before importing.

TO USE:
1. Host this folder on any HTTPS static file host (e.g. free hosting plan subject to its terms), then open URL in iPhone Safari.
2. Share > Add to Home Screen. Open it once online to pre-cache the app shell.
3. Turn on airplane mode and test startup / saved waypoints before the trip.
4. Import locally saved .geojson for parcels or boundary data using the file picker. Export backups periodically.

LEGAL SOURCES CHECKED 2026-11-17:
USGS National Map licensing: https://www.usgs.gov/faqs/what-are-terms-uselicensing-map-services-and-data-national-map
USGS topographic third-party exceptions: https://www.usgs.gov/faqs/are-usgs-topographic-maps-copyrighted
Texas GIO parcel portal: https://geographic.texas.gov/stratmap/land-parcels
OSM public tile offline restrictions: https://operations.osmfoundation.org/policies/tiles/
