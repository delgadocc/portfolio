# Global Methane Monitoring for Rice: From Research to Operations

**Period**: 2023–2026 | **Role**: Research Scientist | **Partners**: CGIAR, CIMMYT, IRRI, Agricultural Research Organizations (USA, Peru, Uruguay, Panama)

## Description

Building on doctoral thesis innovations in satellite-AI methane detection, the **Global Methane Hub (GMH)** project translates research algorithms into operational tools for quantifying emissions from rice agriculture worldwide. With rice contributing ~10% of agricultural methane emissions and covering 160+ million hectares, satellite-based monitoring offers unprecedented potential for climate-smart rice intensification and carbon credit verification.

### The Challenge

- Rice paddies span four continents with limited coordinated emissions monitoring
- Current estimation relies on production statistics × emission factors; lacks spatial verification
- Farmers have no objective feedback on methane losses—opportunity to incentivize mitigation
- Carbon markets need credible, scalable emissions data for rice-credit validation

### The Solution

Operational platform integrating:
- **Satellite-AI algorithms** adapted from livestock project for rice paddy detection and methane quantification
- **In-situ validation** networks across 4 countries (USA, Peru, Uruguay, Panama)
- **Carbon accounting framework** converting emission maps to verified reduction credits
- **Farmer-facing dashboard** showing paddy-level emissions and mitigation pathways

## Why Rice (Not Livestock)?

Rice paddies are **spatially tractable**: discrete, seasonal, identifiable from space. Unlike dispersed livestock grazing, rice's structure—flooded fields, crop calendars, known locations—makes it satellite-observable and calibration-friendly. This project proves the operational viability of space-based emissions monitoring for global agriculture.

## Data

- **Satellite Imagery**: Sentinel-1 (radar, all-weather), Sentinel-2 (optical), Sentinel-5P (methane)
- **In-situ Measurements**: Ground-based chamber measurements (4 countries), eddy covariance towers, methane flux sensors
- **Ancillary Data**: Rice planting calendars, field boundaries, soil maps, weather stations
- **Training/Validation**: 1000+ field sites across target countries

## Software

- **Processing Pipeline**: Python, GDAL, Google Earth Engine
- **Machine Learning**: Scikit-learn, XGBoost, TensorFlow (paddy classification + emission prediction)
- **Geospatial Tools**: QGIS, PostGIS, Rasterio
- **Web Platform**: Flask/Django backend, PostgreSQL database
- **Visualization**: Leaflet, Folium, interactive web dashboards
- **Data Management**: AWS S3, Google Cloud Storage

## Outputs

### Scientific
- Validated methodologies for satellite-based rice methane monitoring
- Publications demonstrating 4-country accuracy and applicability

### Operational
- **Global rice methane maps** at 100m resolution, updated seasonally
- **Farmer dashboards** showing paddy emissions and mitigation recommendations
- **Carbon accounting system** quantifying verified emission reductions for credit issuance
- **Data pipeline** processing satellite and ground data in real-time

### Policy
- **Emissions baseline** for participating countries (USA, Peru, Uruguay, Panama)
- **Climate action framework** for rice-producing regions (linking emissions to incentives)
- Open data products for climate research and policy development

---

**Related Work**: Methodologies developed in the [Livestock Methane thesis](./livestock-methane.md) provide foundational AI-satellite techniques. [EcoProMIS](./ecoproMis.md) complements with multi-scale Earth observation for broader agricultural climate integration.
