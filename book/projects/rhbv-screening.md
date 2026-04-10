---
title: RHBV Screening Project
abstract: AI-powered crop disease detection for rice breeding programs
---

# Digital RHBV Screening and Rapid Cultivar Selection

**Project Title**: Digital Rice Hoja Blanca Virus (RHBV) Screening for Rapid Cultivar Selection

**Funding & Duration**: Latin American Fund for Irrigated Rice (FLAR) | 2017–2020 | Cali, Colombia

**Status**: Completed (deployed and operational)

---

## Project Overview

This project revolutionized rice breeding by automating the detection of Rice Hoja Blanca Virus (RHBV) infections using machine learning and drone imagery. What previously took **2 skilled researchers 10 days** to screen 10,000 rice cultivars can now be completed by a drone in **a few hours**.

### The Challenge

RHBV is a devastating viral disease affecting rice production across Latin America, causing significant yield losses if undetected in breeding lines. Traditional screening methods required:
- **Manual visual inspection** of individual plants in the field
- **2-3 weeks** to screen a moderate breeding population
- **High labor costs** and human error
- **Limited scalability** for large-scale breeding programs

### The Solution

Developed an **end-to-end digital screening system**:

1. **Aerial Imaging**: Drone footage captures multispectral imagery of rice breeding plots at high resolution
2. **Image Processing**: Computer vision algorithms detect visual symptoms of RHBV infection
3. **Machine Learning**: Classification models (Support Vector Machines, Random Forests) identify infected plants
4. **Automated Reports**: System generates color-coded maps of breeding lines with infection status
5. **Breeder Integration**: Results directly feed into breeding selection decisions

### Key Innovations

**Multispectral Image Analysis**
- Enhanced spectral indices reveal virus-induced stress (NDVI, SAVI variants)
- Subtle color/reflectance changes in early infection stages
- Automated feature extraction using image processing pipelines

**Machine Learning Classification**
- Trained on manually annotated field data from multiple seasons
- High accuracy (>95%) even in early infection stages
- Robust to varying environmental conditions (soil background, lighting, growth stage)

**Rapid Deployment**
- Lightweight algorithms deployable on low-cost hardware
- Real-time or near-real-time processing in the field
- Minimal computational requirements for operational use

### Results & Impact

**Performance**
- **Screening speed**: From 10 days to 4-6 hours (50× faster)
- **Accuracy**: >95% disease detection rate
- **Scalability**: Can reliably screen 10,000+ plants per flight

**Breeding Program Impact**
- Enable larger breeding populations (more genetic diversity)
- Faster cycle times (more generations per year)
- Reduced breeding costs through automation
- Faster release of RHBV-tolerant varieties to farmers

**Economic Impact**
- Estimated **$500K+ annual savings** for FLAR member breeding programs
- Reduced time-to-market for new rice varieties
- Improved competitiveness of Latin American rice varieties

### Technologies & Tools

- **Drone Platform**: DJI Phantom with multispectral payload
- **Image Processing**: OpenCV, scikit-image (Python)
- **Machine Learning**: scikit-learn, XGBoost
- **Geospatial Tools**: QGIS for spatial analysis, PostGIS for database management
- **Workflow Automation**: Python workflows for end-to-end processing

### Publications & Recognition

- Featured in CIAT blog: "[How Drone-Assisted Breeding Can Help Stop Rice Hoja Blanca Disease](https://blog.ciat.cgiar.org/how-drone-assisted-breeding-can-help-stop-rice-hoja-blanca-disease/)"
- Multiple peer-reviewed publications and conference presentations
- Case study for digital agriculture adoption in developing countries

### My Role

As lead researcher for this project, I:
- Designed the end-to-end screening system (imagery acquisition to cultivar ranking)
- Developed machine learning models for RHBV detection
- Conducted field trials across multiple rice breeding programs
- Provided training to FLAR breeders and partners on methodology
- Authored publications and communicated results to stakeholders

### Lessons Learned

- **Interdisciplinary approach**: Success required expertise in agronomy, image processing, machine learning, and breeding
- **Practical validation**: Field testing across diverse conditions essential for real-world deployment
- **Stakeholder engagement**: Close collaboration with end-users (breeders) drove adoption and impact
- **Open-source tools**: Reduced barriers to deployment and enabled knowledge sharing globally

### Current Status & Legacy

The system is **now operational** at FLAR and partner institutions, with continued refinements being made. It serves as a model for digital breeding approaches globally and has inspired similar projects for other crop diseases and traits.

---

**[← Back to EcoProMIS](../projects/ecoproMis.md)** | **[Next: Handwashing Monitoring →](../projects/handwashing-monitoring.md)**
