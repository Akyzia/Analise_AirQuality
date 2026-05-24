# Interactive Geospatial WebGIS with Google Earth Engine and Folium

Interactive geospatial visualization system developed in Python using **Google Earth Engine**, **Folium**, and **GeoPandas** within the Google Colab environment.

The notebook provides an interactive WebGIS interface for spatial visualization, raster visualization, vector integration, coordinate interaction, dual map comparison, minimap support, and Earth Engine data exploration.

---

# Overview

This project demonstrates the integration between:

- Google Earth Engine;
- Folium/Leaflet;
- GeoPandas;
- Raster visualization tools;
- Interactive widgets.

The notebook creates an interactive geospatial environment capable of visualizing raster and vector datasets directly inside Google Colab.

The workflow is designed for applications involving:

- geospatial analysis;
- environmental monitoring;
- remote sensing;
- raster visualization;
- GIS dashboards;
- Earth Engine interactive applications.

---

# Main Features

The notebook includes:

- interactive web map generation;
- Google Earth Engine integration;
- raster visualization;
- dual map comparison;
- shapefile visualization;
- coordinate interaction;
- minimap support;
- custom legends;
- browser visualization;
- interactive widgets;
- geospatial plotting.

---

# Google Earth Engine Initialization

The notebook initializes the Google Earth Engine API:

```python
import ee
ee.Initialize()
```

This enables direct access to Earth Engine datasets and processing capabilities.

---

# Interactive Web Map

The project uses Folium and Leaflet to create interactive maps.

```python
import folium
```

The map environment supports:

- zoom interaction;
- layer visualization;
- multiple basemaps;
- raster overlays;
- vector overlays.

---

# Dual Map Comparison

The notebook uses the Folium DualMap plugin for side-by-side visualization.

```python
from folium.plugins import DualMap
```

This functionality is useful for:

- temporal comparisons;
- before/after analysis;
- raster comparison;
- environmental change analysis.

---

# MiniMap Support

The project includes a minimap plugin:

```python
from folium.plugins import MiniMap
```

The minimap improves spatial navigation and user interaction.

---

# GeoPandas Integration

Vector datasets are manipulated using GeoPandas.

```python
import geopandas as gpd
```

Supported operations include:

- shapefile loading;
- vector visualization;
- geometry handling;
- spatial integration.

---

# Raster Visualization

Raster datasets are handled using Rasterio.

```python
import rasterio
```

Raster visualization includes:

- raster plotting;
- spatial extent extraction;
- colormap rendering;
- geospatial visualization.

---

# Interactive Widgets

The notebook uses interactive widgets for interface interaction.

```python
import ipywidgets as widgets
```

Widgets are used for:

- user interaction;
- dynamic controls;
- interface customization;
- interactive visualization.

---

# Visualization and Plotting

The notebook uses Matplotlib for graphical rendering.

```python
import matplotlib.pyplot as plt
```

Applications include:

- raster plotting;
- charts;
- color rendering;
- scientific visualization.

---

# Libraries Used

```python
ee
geemap
folium
geopandas
ipywidgets
pandas
rasterio
matplotlib
numpy
branca
```

---

# Installation

This project was developed for Google Colab.

Install the required libraries before running the notebook:

```python
!pip install geemap earthengine-api
```

If necessary:

```python
!pip install geopandas rasterio branca
```

---

# Google Earth Engine Authentication

Before executing the notebook, authenticate your Earth Engine account:

```python
import ee
ee.Authenticate()
ee.Initialize()
```

---

# Project Structure

```text
Interactive_WebGIS/
│
├── cod.ipynb
├── README.md
└── assets/
```

---

# How to Run

## Google Colab

1. Upload the notebook to Google Colab;
2. Install the required libraries;
3. Authenticate Google Earth Engine;
4. Execute the notebook cells sequentially;
5. Interact with the generated WebGIS environment.

---

# Main Technologies

- Python
- Google Earth Engine
- Folium
- Leaflet.js
- GeoPandas
- Rasterio
- Matplotlib
- Google Colab

---

# Applications

Possible applications include:

- environmental monitoring;
- land use analysis;
- remote sensing visualization;
- WebGIS systems;
- geospatial dashboards;
- Earth observation studies;
- raster analysis;
- geospatial education.

---

# Important Notes

- A Google Earth Engine account is required;
- The notebook was designed for Google Colab;
- Some datasets may require internet access during execution;
- Earth Engine authentication is mandatory before processing.

---

# Author

Developed by Bruna Rocha.