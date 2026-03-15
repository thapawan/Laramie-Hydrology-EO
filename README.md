***

# **Laramie Water Cycle – Earth Observation Study**

This repository contains the data, notebooks, and documentation for the **Laramie Hydrologic Story Map Project**, which integrates **in‑situ field observations**, **360° Virtual Field Trips**, and **NASA Earth Observation datasets** to explore the hydrologic architecture of the Laramie Range.

The project demonstrates how **field-based hydrology**, **remote sensing**, and **interactive visualization** can be combined to support environmental learning and geographic literacy.

***

## 🚰 **Project Overview**

This study brings together:

*   **360° Virtual Field Trips (VFTs)** for immersive hydrologic context
*   **NASA & USGS Earth Observation datasets** for surface water and vegetation analysis
*   **Medial Axis Transform (MAT)** for extracting and analyzing river centerlines
*   **GEE‑based time‑series analysis** for NDVI, NDWI, and seasonal hydrologic patterns

The approach supports both **research** and **education**, allowing students and viewers to explore hydrology using real data and interactive tools.

***

## 🛠 **Tools & Technologies Used**

### **🌍 Google Earth Engine (GEE)**

*   Time‑series analysis
*   Landsat 5/7/8 and Sentinel‑2 surface reflectance
*   NDVI, NDWI, EVI, and threshold water detection methods

### **🛰 NASA Virtual Field Trip (ASU – NASA SMD)**

*   360° environment to contextualize geomorphic and hydrologic features
*   Used for geovisualization and teaching environmental literacy

### **🕳 Medial Axis Transform (MAT)**

*   Extracts river centerlines from binary masks
*   Useful for hydrology, geomorphology, and river‑network modeling

### **📦 Supporting Libraries**

*   Python, NumPy, Pandas
*   Geopandas, Rasterio
*   Matplotlib, Plotly
*   scikit‑image, OpenCV

***

## 📁 **Repository Structure**

    Laramie-Water-Cycle/
    ├── notebooks/        # Jupyter notebooks (GEE API, NDVI/NDWI processing, MAT extraction)
    │   ├── NDVI_time_series.ipynb
    │   ├── NDWI_analysis.ipynb
    │   └── MAT_centerline_extraction.ipynb
    │
    ├── assets/           # Photographs, VFT metadata, shapefiles, site notes
    │   ├── field_photos/
    │   ├── metadata/
    │   └── vft_screenshots/
    │
    ├── docs/             # Project abstract, HydroMorphNet framework, diagrams
    │   ├── abstract.pdf
    │   └── hydromorphnet_overview.pdf
    │
    ├── README.md
    └── LICENSE

***

## 📊 **Core Analyses Included**

*   Vegetation greenness (NDVI) modeling
*   Surface water detection (NDWI, mNDWI)
*   Seasonal hydrologic variability
*   River centerline extraction using MAT
*   Visual integration with VFT field sites
*   Laramie Range hydrologic story for education

***

## 🗺 **Interactive Products**

### **🎥 Virtual Field Trip (VFT)**

**Laramie's Water Cycle – An Earth Observation Field Study**  
👉 <https://p.tourit.etx.asu.edu/v1fshqa2/7h0of1mq4paem4b/index.html>

### **📖 ArcGIS StoryMap**

**The Hydrologic Architecture of the Laramie Range**  
👉 <https://storymaps.arcgis.com/stories/aef97d6acc2a4ee0beb4552f627b89d4>

### **📝 Blog Post**

**Laramie’s Water Cycle: An Earth Observation Field Study**  
👉 <https://www.blogger.com/blog/post/edit/4734384758171839741/7887712852593980658?hl=en>

***

## 🧠 **Research Context**

This project is part of a larger effort to:

*   Integrate **Earth Observation** into hydrology education
*   Develop reproducible **remote sensing workflows**
*   Demonstrate **HydroMorphNet**, a framework linking morphology & hydrologic signals
*   Connect field experiences with satellite‑based environmental understanding

***

## 🚀 **How to Use This Repository**

Clone the repo:

```bash
git clone https://github.com/YOUR-USERNAME/Laramie-Water-Cycle.git
cd Laramie-Water-Cycle
```

Open any notebook:

```bash
jupyter lab
```

Ensure you have the necessary Python packages installed:

```bash
pip install -r requirements.txt
```

***

## 🤝 **Contributions**

Contributions, improvements, or suggestions are welcome.  
Please open an issue or submit a pull request.

***

## 📜 **License**

This project is released under the **MIT License** unless otherwise noted.

***

