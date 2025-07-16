# Lake Detection with NDWI (Google Earth Engine + Python)

This Jupyter Notebook helps you detect water bodies (like lakes) using Sentinel-2 satellite imagery from Google Earth Engine.

## Features
- Draw your area of interest on a map
- Set NDWI thresholds and polygon filters
- Export resulting lake geometries to Google Drive as GeoJSON

## Setup Instructions

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Authenticate with Earth Engine

The first time you run the notebook, you'll be prompted to authenticate. Just follow the instructions in the output.

### 3. Run the notebook

Use Jupyter or Google Colab to run the notebook:
```bash
jupyter notebook lakes_in_argentina.ipynb
```

## Configuration

You can adjust detection parameters at the beginning of the notebook:
- NDWI threshold
- Cloud cover tolerance
- Minimum polygon area
- Buffer size for merging close lakes

## Output

Detected lakes will be exported to your Google Drive in the `EarthEngine` folder.

