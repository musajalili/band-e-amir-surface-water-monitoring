# Surface Water Monitoring and Water Storage Mapping  
## A Case Study of Band-e Amir Lake, Bamyan, Afghanistan

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18784299.svg)](https://doi.org/10.5281/zenodo.18784299)

---

## Project Overview

This repository contains the implementation and workshop report for:

**Surface Water Body Monitoring & Water Storage Mapping**  
Study Area: Band-e Amir Lake, Bamyan, Afghanistan  

The study integrates satellite remote sensing, hydrological analysis, and climate-driven water storage assessment using:

- Google Earth Engine (GEE)
- Landsat-8/9 Collection 2 Level-2
- MODIS Surface Reflectance
- GRACE / GRACE-FO Terrestrial Water Storage Anomalies (TWSA)

The objective is to evaluate seasonal lake surface temperature dynamics, long-term lake area variability, and regional-to-global water storage trends.

---

## 🌍 Study Area

The case study focuses on **Band-e Amir National Park**, located in Bamyan Province, central Afghanistan.

- Elevation: ~3,000 meters  
- Coordinates: 34.83°N, 67.23°E  
- Afghanistan’s first national park  
- UNESCO World Heritage Site  
- Hydrologically sensitive high-altitude lake system  

---

## 🛰️ Data Sources

- Landsat 8 & 9 (Collection 2 Level-2)
- MODIS Surface Reflectance
- GRACE / GRACE-FO Mascon (JPL RL06.3 v04)
- Study Area Boundary Datasets

All satellite processing was conducted using Google Earth Engine.

---

## Methodology Summary

### 1️⃣ Surface Water Temperature (2024–2025)
- LST derived from Landsat ST_B10 band  
- NDWI-based water masking  
- QA_PIXEL cloud masking  
- Seasonal temperature variability analysis  

### 2️⃣ Lake Area Monitoring (2001–2023)
- MODIS-based surface water extraction  
- Long-term variability assessment  
- Drought-related fluctuation analysis  

### 3️⃣ GRACE Water Storage Analysis (2002–2025)
- Terrestrial Water Storage Anomalies (TWSA)
- Linear trend estimation (cm/year)
- Regional and global comparison  

---

# 💻 Google Colab Notebooks

All analyses are fully reproducible via Google Colab.

---

## 🔹 GRACE Water Storage Analysis

Terrestrial Water Storage Anomaly trend analysis for:

- Afghanistan  
- Asia  
- Global scale  

📎 **Colab Link:**  
https://colab.research.google.com/drive/1tsdq0eHVM001RR9N7-1VZ9Z_xpmcABX4?usp=sharing 

---

## 🔹 Lake Surface Temperature (LakeLST) Analysis

Includes:

- Landsat 8/9 LST processing  
- NDWI water masking  
- Time-series extraction  
- Seasonal visualization  

📎 **Colab Link:**  
https://colab.research.google.com/drive/1yhO_yYAgZUqpe0p67-arie81zz31XMbR?usp=sharing 

---

## 📂 Repository Structure
band-e-amir-surface-water-monitoring/<br>
│<br>
├── README.md<br>
├── LICENSE<br>
├── gee_script/<br>
│ └── band_e_amir_surface_water.js<br>
│
├── notebooks/
│ ├── GRACE_analysis.ipynb
│ └── LakeLST_analysis.ipynb
│
├── report/
│ └── WorkshopReport.pdf
│
└── results/
└── figures/

## 📖 Citation

If you use this work, please cite:

Jalili, M. (2025).  
*Surface Water Monitoring and Water Storage Mapping: A Case Study of Band-e Amir Lake, Bamyan, Afghanistan.*  
Zenodo. https://doi.org/10.5281/zenodo.18784299

---

## 📜 License

This project is licensed under the MIT License.  
See the LICENSE file for details.

---

## 🔬 Keywords

Remote Sensing • Google Earth Engine • GRACE • Landsat • Lake Surface Temperature • Hydrology • Afghanistan • Water Storage • Climate Variability

