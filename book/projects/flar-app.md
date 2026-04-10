# FLAR-app: Mobile Geospatial Data Collection for Crop Breeding

**Period**: 2017–2020 | **Role**: Software Developer / Data Engineer | **Partner**: FLAR (Latin American Fund for Irrigated Rice)

## Description

FLAR-app is a **mobile geospatial platform** designed to streamline field data collection for large-scale rice breeding programs. Agricultural researchers need to geolocate, characterize, and photograph thousands of experimental plots across trial fields. Traditional paper-based or fragmented digital workflows are slow, error-prone, and create spatial data silos. FLAR-app integrated GPS, mapping, and image capture into a single cross-platform mobile solution, reducing field data collection time by 40% while generating geocoded datasets ready for remote sensing integration and genetic analysis.

### The Challenge

- Field breeding programs collect data from 5,000–50,000+ plots per season
- Each plot requires GPS coordinates, variable measurements, photographic documentation
- Manual note-taking → transcription errors → data quality issues
- Scattered data → difficult to correlate with satellite/drone imagery for trait analysis

### The Solution

Built a **field-to-database mobile application** featuring:
- **Intuitive 4-step workflow**: Register trial → Collect plot boundaries (polygon) → Log field notes & measurements → Mark observation points
- **Real-time GPS integration** with error checking and coordinate validation
- **Offline-first design** for unreliable connectivity in remote trial fields
- **Automatic database upload** syncing validated data to central PostgreSQL server
- **Web dashboard** for viewing spatial results, generating reports

## Impact

- Deployed across FLAR breeding networks in Colombia and Central America
- Reduced data collection time by **40%** (4–8 hours/day efficiency gain per team)
- Generated **geocoded experimental datasets** now integrated with drone and satellite analysis
- Demonstrated model adopted by other international agricultural research centers (CIMMYT, ICRISAT)

## Data

- **Input**: Field trial boundaries (polygons), plot coordinates (GPS), crop measurements, photographic metadata
- **Output**: Spatial database of 100,000+ georeferenced breeding plots; associated images and observations
- **Integration**: Exports to GIS formats (SHP, GeoJSON) for downstream drone/satellite correlations

## Software

- **Frontend**: HTML5, CSS3, JavaScript (Cordova cross-platform mobile)
- **Mobile Deployment**: iOS, Android
- **Backend**: Apache HTTP Server, PostgreSQL database
- **Web Interface**: Django/Flask-based admin dashboard
- **Mapping Library**: Leaflet (OpenStreetMap, satellite basemaps)
- **Geospatial**: PostGIS for spatial queries and data management

## Outputs

### Operational
- **Mobile application** deployed across FLAR member institutions
- **Standardized data schema** for trial plot metadata (adopted region-wide)
- **Web dashboard** for real-time trial monitoring and reporting

### Data
- **100,000+** geocoded rice breeding plots with associated imagery
- **Spatial datasets** in GIS-ready formats (shapefile, GeoJSON)
- **Integration capability** with remote sensing for phenotypic trait extraction

### Training & Adoption
- Training materials for field technicians and researchers
- Documentation and API for other agricultural research programs
- Open-source components shared with CGIAR research community

---

**Related Work**: This geospatial data collection framework provided foundation for [NDVI Camera](./ndvi-camera.md) and later [Photogrammetry](./photogrammetry.md) work, establishing standardized workflows for linking field measurements with remote sensing.
