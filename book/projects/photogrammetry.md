# Drone-Based Photogrammetry: High-Precision 3D Site Mapping

**Period**: 2021–2023 | **Role**: Drone Pilot & Photogrammetry Specialist | **Applications**: Infrastructure surveys, topographic mapping, construction monitoring

## Description

**Photogrammetry** is the science of extracting precise 3D coordinates and measurements from overlapping photographs. Using **Remotely Piloted Aircraft Systems (RPAS)** equipped with high-resolution cameras, this project established protocols for accurate, cost-effective surveying of large sites—generating digital elevation models (DEMs), orthomosaics, and 3D point clouds at centimeter-level accuracy.

### Application Example: Cartago Construction Survey (Aug 2021)

A metalworking company needed precise topographic documentation of a construction site in Cartago, Valle del Cauca, Colombia. Traditional surveying would require weeks of ground crews; photogrammetry delivered results in 2 days.

### The Challenge

- **High-accuracy requirements**: Construction and infrastructure projects need <5cm horizontal and vertical precision
- **Large areas**: Sites spanning hundreds of hectares require efficient flight planning and data collection
- **Complex geometry**: Terrain variations, vegetation, structures demand precise point cloud classification
- **Deliverable diversity**: Clients need multiple products (DEMs, orthomosaics, 3D models) from single survey

### The Solution

Developed a **complete photogrammetry workflow**:

1. **Flight Planning**: Optimized multi-pass flights with 75% image overlap for robust aerotriangulation
2. **Ground Control Points**: Established 29–30 RTK-GPS reference points per flight for absolute accuracy
3. **Sparse Reconstruction**: Structure-from-Motion (SfM) generated thousands of automatically detected tie points
4. **Dense Cloud Generation**: Multi-view stereo matching created dense 3D point clouds (millions of points)
5. **Automatic Classification**: Ground/non-ground classification separating terrain from vegetation/structures
6. **Product Generation**: DEM rasterization, contour extraction, orthomosaic creation, 3D model export

## Survey Details (Cartago Example)

| Parameter | Flight 1 | Flight 2 |
|-----------|----------|----------|
| **Images Acquired** | 311 | 322 |
| **Ground Resolution** | 2.48 cm/px | 2.4 cm/px |
| **GCPs Collected** | 29 | 30 |
| **Aerotriangulation Error (X,Y,Z)** | 1.20m, 1.56m, 3.22m | 1.82m, 3.50m, 5.18m |
| **DEM Resolution** | 4.95 cm/px | 4.17 cm/px |

**Accuracy Compliance**: Errors align with Colombian mapping standard (Resolución 471/2020 IGAC) requiring <30cm horizontal accuracy for <10cm/pixel products.

## Data

- **Flight Data**: High-resolution aerial photography (4000×2250 px, DJI FC3170 camera)
- **Ground Reference**: 29–30 surveyed GCPs per flight (RTK-GPS, ±5cm accuracy)
- **Derived Products**: 
  - Sparse point clouds (structure-from-motion tie points)
  - Dense point clouds (multi-view stereo, millions of 3D coordinates)
  - Ground-classified terrain model
  - DEM raster (4–5cm resolution)
  - Orthomosaic (georeferenced orthophoto)
  - Contour lines (1m equidistance)

## Software

- **Photogrammetry Engine**: Pix4D / Agisoft Metashape (SfM, dense matching, DEM generation)
- **Flight Planning**: DJI Flight Planner (optimal overlap, GCP targeting)
- **GCP Survey**: Trimble RTK-GPS (ground truth acquisition)
- **Data Processing**: GDAL, Rasterio (raster manipulation, format conversion)
- **Point Cloud Analysis**: CloudCompare (classification, filtering, visualization)
- **GIS Integration**: QGIS (vector/raster analysis, 3D model viewing)

## Outputs

### Geospatial Products
- **DEM (Digital Elevation Model)**: GeoTIFF raster (4–5cm resolution), terrain representation
- **Orthomosaic**: Georeferenced orthophoto (aerial view corrected for terrain distortion)
- **Contour Lines**: Vector dataset (DXF/SHP) at 1m vertical intervals for surveying
- **Point Cloud**: LAS/LAZ format with RGB color and classification (ground/non-ground)

### 3D Models
- **Surface Model (MDS)**: Digital surface model including vegetation and structures (FBX format)
- **Terrain Model (MDT)**: Bare-earth digital terrain model (FBX format)
- **Applications**: 3D visualization, virtual walkthroughs, volumetric calculations

### Documentation
- **Technical Report**: Methodology, accuracy assessment, error analysis
- **Flight Plans**: Visualization of flight paths, image overlap, GCP distribution
- **Specifications**: Resolution, accuracy, datum, projection (standardized for GIS workflows)

### Data Formats (Cartago Deliverables)
- **AUX POINTS** (SHP): Calibration reference points
- **MARUT POINTS** (SHP): Primary GCP dataset
- **CURVES** (DXF/SHP): Extracted contour lines
- **DEM** (GeoTIFF): Elevation raster
- **ORTO** (GeoTIFF): Orthomosaic
- **MDS/MDT** (FBX): 3D surface and terrain models

## Impact & Applications

- **Infrastructure**: Construction monitoring, quarry mapping, bridge/road surveys
- **Disaster Response**: Rapid post-earthquake/flood site assessment
- **Environmental**: Coastal erosion, landslide deformation monitoring
- **Agriculture**: Large-scale field topography for irrigation planning
- **Archaeology**: Cultural heritage documentation and 3D reconstruction

---

**Related Work**: Photogrammetry provides high-resolution terrain for precision agriculture projects ([NDVI Camera](./ndvi-camera.md), [EcoProMIS](./ecoproMis.md)). 3D data feeds into farm planning and environmental impact assessments.
