# Livestock Methane Monitoring: Satellite-AI for Climate Action

**Period**: 2021–2025 | **Role**: Doctoral Researcher | **Institution**: University of Otago, New Zealand

## Description

Livestock agriculture is a major contributor to global greenhouse gas emissions, responsible for ~14% of anthropogenic methane (CH₄). Traditional ground-based monitoring methods are costly, sparse, and labor-intensive, leaving vast grazing regions unmapped. This research developed **AI-powered satellite algorithms** to detect and quantify methane emissions from livestock in New Zealand—one of the world's largest pastoral nations—demonstrating that space-based observations can revolutionize emissions accounting and climate policy.

### The Challenge

- Ground monitoring stations exist at <500 locations worldwide; pastoral lands cover billions of hectares
- Current livestock emissions estimates rely on statistical models and incomplete inventory data
- Need for objective, scalable, satellite-based verification of methane hotspots
- Livestock methane is chemically distinct from other sources (coal, wetlands, rice)—difficult but critical to isolate

### The Solution

Developed **CNN-based satellite emulators** trained on physics-based methane transport signatures to:
- Extract methane signals from multispectral satellite imagery (Sentinel-5P)
- Attribute emissions to livestock vs. other sources using geospatial and meteorological context
- Generate high-resolution methane emission maps over pastoral regions of New Zealand
- Validate against airborne surveys and ground validation data

## Key Innovation

Unlike rice paddies (which are spatially discrete and seasonal), livestock grazing is dispersed across variable terrain. This thesis tackled the harder problem: **detecting and geolocating distributed, persistent methane sources** from pastoral systems—a skill directly transferable to operational climate monitoring.

## Recognition

🏆 **2024 Thesis Award** — *Space for Planet Earth Challenge* (ESA's flagship innovation award recognizing solutions for Earth observation)

📚 **2023 Google Fellowship** — *Selected as Fellow* for research advancing climate-smart agriculture through satellite technology

## Data

- **Satellite Imagery**: Sentinel-5P/TROPOMI (multispectral, global coverage)
- **Validation Data**: Airborne surveys (New Zealand), ground stations (NOAA networks)
- **Geospatial Context**: Land use maps, livestock distribution (FAO), terrain models (SRTM)
- **Training Dataset**: Physics-based methane transport simulations + satellite observations

## Software

- **Deep Learning**: Python, TensorFlow, PyTorch (CNN architecture development)
- **Geospatial Analysis**: GDAL, Rasterio, GeoPandas, QGIS
- **Data Processing**: NumPy, SciPy, Pandas, Dask (large-scale satellite data)
- **Validation**: Scikit-learn, Matplotlib, statistical analysis
- **Cloud Processing**: Google Earth Engine (GEE), AWS S3

## Outputs

### Academic
- Peer-reviewed publications (details in [Publications](../publications.md))
- Thesis submission to University of Otago (2025)
- Conference presentations at EGU, AGU, climate conferences

### Technical
- Trained deep learning models (open to research license)
- Processing pipelines for Sentinel-5P methane retrieval
- Uncertainty quantification and validation protocols
- Code repository (publication pending)

### Geospatial
- **High-resolution methane maps** over New Zealand pastoral regions (100m–1km resolution)
- **Emission hotspot identification** correlated with livestock distribution
- **Climate policy integration** — framework for satellite-based emissions verification

---

**Next Steps**: Operational deployment planned through [GMH Project](./gmh.md) extending this livestock methodol to rice systems internationally.
