# Drone Flight Profile Planner

## Code Libraries

- **[Leaflet](https://leafletjs.com/)** (BSD-2-Clause) — interactive map display and waypoint placement
- **[Chart.js](https://www.chartjs.org/)** (MIT) — terrain and altitude profile chart
- **[html2canvas](https://html2canvas.hertzen.com/)** (MIT) — PNG export of map and profile
- **[FastAPI](https://fastapi.tiangolo.com/)** (MIT) — Python backend API framework
- **[Uvicorn](https://www.uvicorn.org/)** (BSD-3-Clause) — ASGI web server
- **[Rasterio](https://rasterio.readthedocs.io/)** (BSD-3-Clause) — GeoTIFF terrain data reading
- **[pyproj](https://pyproj4.github.io/pyproj/)** (MIT) — coordinate reference system transformation between WGS84 and OSGB36

## Map Tiles

- **[CartoDB Voyager](https://carto.com/basemaps/)** — map tile layer  
  © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors © [CARTO](https://carto.com/attributions)

## Terrain Data

- **[Environment Agency LiDAR Composite Digital Terrain Model (DTM) 1m](https://www.data.gov.uk/dataset/lidar-composite-digital-terrain-model-dtm-1m)** — bare earth elevation  
  © Environment Agency copyright and/or database right 2024. Open Government Licence.

- **[Environment Agency LiDAR Composite Digital Surface Model First Return (DSM) 1m](https://www.data.gov.uk/dataset/lidar-composite-digital-surface-model-dsm-1m)** — first-return surface elevation including buildings and vegetation  
  © Environment Agency copyright and/or database right 2024. Open Government Licence.

  Terrain data is accessed live via the Environment Agency Web Coverage Service (WCS) and covers England and Wales.

## Regulatory Reference

- Altitude ceiling calculations are based on UK drone regulations published by the **[Civil Aviation Authority (CAA)](https://www.caa.co.uk/drones/)**.
  - Rule A: maximum 120m vertically above the ground directly below
  - Rule B: maximum 120m from the nearest ground surface in three-dimensional Euclidean distance
