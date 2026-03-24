# SplatTwin: A Multilayer 3D Geospatial Digital Twin Framework

SplatTwin is a research-driven repository for developing a multilayer 3D geospatial digital twin framework that integrates semantic city models, surface-based representations, and neural rendering techniques (e.g., Gaussian Splatting) for urban analysis and monitoring.

---

## 📌 Overview

This project aims to bridge different paradigms of 3D geospatial representation into a unified framework:

- **Semantic Models** (e.g., CityGML)
- **Geometric Models** (e.g., Surface Mesh / Semantic Mesh)
- **Radiometric Models** (e.g., Gaussian Splatting / Neural Rendering)

The integration enables advanced applications such as:
- Urban change detection (multi-temporal analysis)
- Digital twin-based monitoring
- Environmental and spatial analysis
- Immersive visualization (WebGIS, VR/MR)

---

## 🎯 Research Objectives

- Develop a **multilayer 3D geospatial basemap**
- Integrate **semantic, geometric, and radiometric representations**
- Enable **multi-scale and multi-temporal analysis**
- Support **digital twin applications for urban environments**
- Explore a **canonical data model** across representations

---

## 🧱 System Architecture

The framework is structured into three main layers:

### 1. Backend
- Data storage (PostgreSQL/PostGIS, 3DCityDB)
- File-based storage (point clouds, meshes, splats)
- Data ingestion pipelines (UAV LiDAR, photogrammetry, 360 imagery)

### 2. Middleware
- Data processing workflows
- AI/ML components (segmentation, reconstruction)
- Conversion tools:
  - CityGML ↔ Mesh
  - Mesh ↔ Gaussian Splatting
- Spatial analysis modules

### 3. Frontend
- Web-based visualization (CesiumJS, MapStore)
- 3D streaming (Cesium Ion / 3D Tiles)
- Immersive visualization (Unity, MR/VR)
- User interaction and query interface

---

## 🧪 Methodology

The workflow includes:

1. **Data Acquisition**
   - UAV LiDAR (metric)
   - Aerial imagery (metric & non-metric)
   - 360° imagery (e.g., GoPro Max)

2. **3D Reconstruction**
   - CityGML LoD1–LoD2 generation
   - Surface mesh reconstruction
   - Neural rendering (3D Gaussian Splatting)

3. **Integration**
   - Multi-representation alignment
   - Semantic enrichment
   - Cross-representation mapping

4. **Evaluation**
   - Geometric accuracy
   - Radiometric consistency
   - Semantic completeness
   - Visual quality (PSNR, SSIM, LPIPS)

5. **Applications**
   - Urban change analysis
   - Digital twin simulation
   - Infrastructure monitoring

---

## 📂 Repository Structure

```
splattwin/
│
├── data/
│   ├── raw/                # Raw datasets (LiDAR, imagery)
│   ├── processed/          # Processed outputs
│
├── models/
│   ├── citygml/            # CityGML models
│   ├── mesh/               # Surface/semantic meshes
│   ├── splatting/          # Gaussian splatting models
│
├── workflows/
│   ├── preprocessing/      # Data preparation
│   ├── reconstruction/     # 3D reconstruction
│   ├── integration/        # Multi-layer integration
│
├── experiments/
│   ├── small_scale/        # ITB Campus (~25 ha)
│   ├── large_scale/        # Jatinangor (~400 ha)
│
├── docs/
│   ├── reports/            # Monthly reports
│   ├── papers/             # Drafts and publications
│   ├── figures/            # Diagrams and illustrations
│
├── notebooks/              # Analysis notebooks
├── scripts/                # Processing scripts
└── README.md
```

## 📊 Study Areas

- **ITB Campus (Bandung)** — Small-scale validation (~25 ha)
- **Jatinangor Education Area** — Large-scale validation (~400 ha)

---

## 🔄 Current Progress

- ✔ Methodology design completed
- ✔ Small-scale experiment completed
- ✔ Large-scale experiment ongoing
- ✔ 2 conference papers completed
- ✔ 1 journal paper in preparation
- ⏳ Multi-temporal data acquisition (non-metric camera)

---

## 🚀 Future Work

- Multi-temporal change analysis
- Canonical data model development
- Real-time digital twin integration
- AI-based semantic extraction from neural models
- Web-based interactive digital twin platform

---

## 🤝 Contributors

- Dr. Deni Suwardhi (ITB)
- Research team and collaborators

---

## 📄 License

This repository is intended for research and academic purposes.  
License details will be defined in future updates.

---

## 📬 Contact

For collaboration and inquiries:

**Dr. Deni Suwardhi**  
Institut Teknologi Bandung (ITB)  
Spatial Systems and Cadastre Research Group  

---

## ⭐ Notes

This repository is part of ongoing research related to:
- Digital Twin
- 3D Geospatial Modeling
- AI for Urban Analysis
- Multi-representation spatial data integration

