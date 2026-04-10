# Low-Cost Multispectral Camera for Crop Health Monitoring

**Period**: 2021–2023 | **Role**: Hardware & Software Developer | **Partners**: CGIAR, CCAFS, CIAT

## Description

Access to multispectral imagery is critical for precision agriculture and crop health monitoring—yet commercial systems cost $10,000–$50,000, limiting adoption in resource-constrained farming communities. This project developed a **low-cost, open-hardware solution** built on Raspberry Pi and multispectral camera modules to enable farmers and researchers to generate NDVI (Normalized Difference Vegetation Index) maps from their own fields for <$500 total cost.

### The Challenge

- Standard NDVI systems (Landsat, Sentinel) lack temporal frequency (16-day revisits) and spatial resolution (10–30m)
- Drone-based multispectral systems require technical expertise and expensive hardware
- Farmers in developing regions cannot justify $15,000+ investments for field-scale monitoring
- Need for autonomous, calibrated acquisition and processing pipeline

### The Solution

Engineered a **Raspberry Pi-based multispectral imaging system** featuring:
- **Hardware**: Raspberry Pi Zero + multispectral camera modules (RGB + NIR bands)
- **Autonomous missions** with scheduled image acquisition and RTK-GPS integration
- **Calibration framework** using reference panels (white, known reflectance) for radiometric accuracy
- **Processing pipeline** (raw sensor data → calibrated reflectance → NDVI indices)
- **Web interface** for farmers to upload images, visualize indices, and receive health alerts

## Impact

- Field-tested with 50+ smallholder farming communities (Colombia, Peru)
- **95% cost reduction** vs. commercial multispectral drones
- Enables **daily NDVI monitoring** vs. fortnightly satellite revisits
- Open-hardware designs released to CGIAR partners; adopted by 5+ research institutions

## Data

- **Acquisition**: Multispectral raw sensor images (RGB, NIR, calibrated reflectance)
- **Calibration**: Reference reflectance panel measurements, radiometric corrections
- **Products**: Georeferenced NDVI maps, vegetation indices (EVI, GNDVI, SAVI)
- **Integration**: Field data exported for downstream ML model training (disease prediction, yield forecasting)

## Software

- **Embedded**: Python, OpenCV (Raspberry Pi real-time processing)
- **Calibration**: NumPy, SciPy, scikit-image (radiometric correction algorithms)
- **Web Frontend**: HTML5, CSS3, JavaScript (Leaflet.js for map visualization)
- **Backend**: Flask, SQLite (lightweight server for resource-constrained environments)
- **Data Processing**: GDAL, Rasterio (GIS-compatible export)

## Outputs

### Hardware & Design
- **Open-source bill of materials** (Raspberry Pi, camera specs, mount assembly)
- **3D-printed field mount** design (GitHub repository)
- **Assembly & calibration guides** for farmers and researchers

### Software
- **Image processing pipeline** (open-source Python scripts)
- **Web dashboard** for geospatial visualization and index computation
- **Deployment tutorial** and troubleshooting documentation

### Scientific & Operational
- **Validation study** comparing Raspberry Pi NDVI vs. drone/satellite (published in remote sensing journal)
- **Field demonstration units** deployed across CGIAR centers (CIAT, IITA, ICRISAT)
- **Integration pathway** showing how farmer-collected data feeds ML models for crop health prediction

### Data Products
- **Georeferenced NDVI maps** at field scale (~1m resolution)
- **Health alert system** notifying farmers of vegetation stress
- **Historical crop index time-series** for yield and disease correlation studies

---

**Related Work**: Demonstrates affordable Earth observation for precision agriculture; complements [EcoProMIS](./ecoproMis.md) multi-scale monitoring and [Photogrammetry](./photogrammetry.md) for integrated field characterization.
