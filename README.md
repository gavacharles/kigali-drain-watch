# kigali-drain-watch

Static GitHub Pages site for Kigali Drain Watch, a map of the City of Kigali's drainage channels with maintenance priorities, priority road crossings, restored wetlands and satellite imagery. Live at https://gavacharles.github.io/kigali-drain-watch/ (demo: https://gavacharles.github.io/kigali-drain-watch/demo.html)

## Contents

| Path | What it is |
|---|---|
| `index.html` | The map application |
| `demo.html`, `demo.mp4`, `demo_still.png` | Short demo page, video and still |
| `segments.json`, `system_labels.json` | Channel stretches and system labels |
| `crossings.json`, `hotspots.json`, `restoration.json`, `places.json`, `boundary.json` | Map layers |
| `satellite.json`, `sat_*.jpg` | Satellite tile index and image tiles |
| `basemap_light.png`, `basemap_dark.png` | Basemaps |
| `.nojekyll` | Serve files as they are on GitHub Pages |

The site is built from `tool/` in the rwanda-flood-watch repository. To view locally, serve the folder (`python -m http.server`) and open http://localhost:8000.

## Sources

Copernicus GLO-30 DEM (channels); © OpenStreetMap contributors (roads, places, stream names); Microsoft Global ML Building Footprints; JRC GHSL R2023A; ESA WorldCover; Copernicus Sentinel-2 and Esri World Imagery; CHIRPS and CMIP6 (design storms); City of Kigali and press reports (hotspots). Rankings come from a screening model; depths are indicative.

Analysis and tool: Gava Charles.
