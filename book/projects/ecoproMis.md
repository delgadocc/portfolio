---
title: EcoProMIS Project
abstract: Multi-scale earth observation for sustainable agriculture and biodiversity
---

# EcoProMIS: Ecological Productivity Management Information System

**Project Title**: Ecological Productivity Management Information System (EcoProMIS)

**Funding & Partner**: UK Space Agency | 2018–2020 | Cali, Colombia

**Status**: Completed (findings inform ongoing research)

---

## Project Overview

EcoProMIS is an integrated earth observation and data analytics system designed to assess the impacts of crop and ecosystem management practices on **biodiversity**, **greenhouse gas emissions**, and **productivity** in tropical agricultural systems, specifically rice and oil palm.

The project synthesizes satellite data, drone imagery, environmental sensors, and crop data to provide holistic insights into agricultural sustainability—moving beyond single-metric optimization toward genuine sustainability assessment.

### Project Objectives

- **Biodiversity Assessment**: Quantify impacts of agricultural management on wildlife and plant species diversity
- **Climate Monitoring**: Track greenhouse gas emissions (particularly methane and nitrous oxide) from managed ecosystems
- **Productivity Optimization**: Maintain or increase crop productivity while reducing environmental impact
- **Decision Support**: Develop tools enabling farmers and policymakers to make evidence-based management decisions
- **Regional Capacity**: Build technical capacity for earth observation applications in tropical agricultural research

### Multi-Scale Remote Sensing

The project operates across three complementary scales:

#### Satellite Layer (Regional Scale)
- **Sensors**: Sentinel-1 (SAR), Sentinel-2 (multispectral), Landsat 8
- **Applications**: Large-scale land use mapping, phenology monitoring, environmental variables
- **Frequency**: Weekly to bi-weekly monitoring across rice and oil palm landscapes
- **Analysis**: Temporal trends in vegetation indices, water availability, soil moisture

#### Drone Layer (Farm Scale)
- **Platforms**: Multi-rotor and fixed-wing drones with RGB and multispectral payloads
- **Resolution**: Sub-meter resolution for detailed crop monitoring
- **Applications**: High-throughput plant phenotyping, pest/disease monitoring, field heterogeneity
- **Timing**: Campaign-based imagery at critical crop growth stages

#### Ground Layer (Plot Scale)
- **Sensors**: Environmental stations (temperature, humidity, soil sensors)
- **Measurements**: Direct greenhouse gas emissions (eddy covariance, chambers), biodiversity surveys
- **Validation**: Ground truth data for calibrating and validating satellite/drone models
- **Sampling**: Intensive measurements in research plots; distributed monitoring across farms

### Key Research Components

**Crop Productivity Monitoring**
- Satellite-derived vegetation indices (NDVI, LAI) predicting yield potential
- Drone imagery for detecting early stress signals (water, nutrient, pest/disease)
- Integration with crop models for yield forecasting
- Site-specific management recommendations

**Greenhouse Gas (GHG) Monitoring**
- Methane (CH₄) and nitrous oxide (N₂O) emissions from rice and oil palm systems
- Relationships between management practices and GHG fluxes
- Satellite proxies for emission hotspots
- Mitigation strategies (water management, fertilizer application timing)

**Biodiversity Assessment**
- Remote sensing indicators of habitat quality and heterogeneity
- Ground surveys of bird, insect, and plant communities
- Relationships between landscape complexity and biodiversity
- Recommendations for agro-ecological intensification

**Data Integration & Analysis**
- Fusion of multi-sensor datasets (satellite, drone, ground, crop)
- Machine learning for pattern discovery and prediction
- Spatial analysis of ecosystem services trade-offs
- Scenario modeling for different management strategies

### Technologies & Tools

- **Remote Sensing Platforms**: Google Earth Engine, QGIS, ArcGIS
- **Data Processing**: Python (xarray, rasterio, GeoPandas) for large-scale data pipelines
- **GIS Analysis**: PostGIS for spatial queries and analysis
- **Machine Learning**: scikit-learn, TensorFlow for crop/ecosystem modeling
- **Drone Processing**: Agisoft Metashape, OpenDroneMap for 3D reconstruction
- **Statistical Analysis**: R for biodiversity and statistical modeling

### Collaborators & Partners

- **UK Space Agency** (funder)
- **International Center for Tropical Agriculture (CIAT)** (lead research institution)
- **University of Otago** (geospatial analysis)
- **National agricultural research programs** (Colombia, regional partners)
- **Farmer cooperatives** (field sites and knowledge exchange)

### My Role

As co-lead coordinator of the earth observation group, I:
- Supervised design and implementation of the multi-scale remote sensing system
- Developed workflows for satellite and drone data processing and analysis
- Led high-throughput plant phenotyping using computer vision and AI
- Trained research teams and farmer collaborators on earth observation methods
- Contributed to publications and presented findings at international conferences
- Coordinated data collection campaigns and field validation studies

### Key Findings & Insights

**Productivity-Sustainability Insights**
- Sustainable practices (e.g., crop diversification, reduced tillage) maintain productivity while reducing GHG emissions
- Satellite data can effectively monitor system productivity and resilience
- Site-specific management based on earth observation data improves outcomes vs. uniform management

**Technological Validation**
- Multi-scale integration of remote sensing data improves accuracy of ecosystem monitoring
- Drone-based phenotyping enables rapid assessment of agricultural practices
- Machine learning significantly enhances the utility of earth observation data for decision-making

**Capacity Building Impact**
- Earth observation technologies are feasible and valuable for tropical agricultural research
- Training programs successfully transfer skills to local researchers and farmers
- Open-source tools enable knowledge sharing and cost-effective deployment

### Publications & Outputs

Multiple peer-reviewed publications, conference presentations, and technical reports documenting:
- Remote sensing methodology and validation
- Biodiversity impacts of agricultural management
- GHG emission patterns and mitigation strategies
- Practical guidance for earth observation application in tropical agriculture

### Data & Tools Access

- Anonymized datasets available for academic research
- Open-source processing scripts shared via GitHub
- Training materials and protocols available for replication

### Legacy & Ongoing Impact

EcoProMIS demonstrated the feasibility and value of integrated earth observation for tropical agriculture. Findings continue to inform:
- Ongoing research projects on sustainable intensification
- Policy frameworks for climate-smart agriculture
- Open-source tool development for agricultural monitoring
- Training programs in earth observation and sustainability assessment

---

**[← Back to Methane Project](../projects/methane-monitoring.md)** | **[Next: RHBV Project →](../projects/rhbv-screening.md)**
