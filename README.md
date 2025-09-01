This repository provides a Google Earth Engine (GEE) workflow to compute, visualize, and export key vegetation indices (NDVI, EVI, RVI, NDRE) from Sentinel-2 SR Harmonized data for a given Area of Interest (AOI).
The script covers cloud masking, index calculation, visualization, and batch export of derived layers.

📌 Features

- Cloud & Cirrus Masking using Sentinel-2 QA60 band

- Sentinel-2 Harmonized SR Collection (COPERNICUS/S2_SR_HARMONIZED)

- Date Range Filtering: January 1, 2025 – February 28, 2025

➕ Computed Vegetation Indices

- NDVI (Normalized Difference Vegetation Index)

- EVI (Enhanced Vegetation Index)

- RVI (Ratio Vegetation Index)

- NDRE (Normalized Difference Red-Edge Index)

🖼️ True Color Composite (Bands B4, B3, B2)

🎨 Custom Palette Legend for indices

📤 Exports processed images to Google Drive in GeoTIFF format

🧮 Vegetation Indices Formulas

NDVI = (NIR − Red) / (NIR + Red)

EVI = 2.5 × (NIR − Red) / (NIR + 6 × Red − 7.5 × Blue + 1)

RVI = NIR / Red

NDRE = (NIRn − RE5) / (NIRn + RE5)

Where:

NIR = B8 (842 nm)

Red = B4 (665 nm)

Blue = B2 (490 nm)

NIRn = B8A (865 nm, narrow NIR)

RE5 = B5 (705 nm, red edge)

📸 Visualization

True Color Composite (Bands 4-3-2)

NDVI, EVI, RVI, NDRE layers with gradient palettes (red → dark green)



