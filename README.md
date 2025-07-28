# ⚡ EV Charging Points Analysis

This project provides data analysis and interactive visualization of electric vehicle (EV) charging points using Python, Pandas, and Folium.

---

## 📁 File Descriptions

- **`EV map1.html`**  
  Interactive map showing the locations of EV charging stations, grouped by **company**.

- **`EV map2.html`**  
  Interactive map showing station distribution by **charging power**:

  - **Fast vs Slow Charging Classification**
    - ⚡ Stations with **Rated Output Power ≥ 22 kW** → **Fast** (green markers)
    - 🔌 Stations with **Rated Output Power < 22 kW** → **Slow** (blue markers)

  - **Marker Clustering**
    - Stations are grouped using the **MarkerCluster** plugin.
    - Zoom out to cluster markers; zoom in to reveal individual stations.

- **`EVChargingAnalysis.ipynb`**  
  Jupyter Notebook with full data analysis and map generation code.

- **`ElectricVehicleChargingPoints.csv`**  
  Raw dataset of EV charging station locations and specifications.

---

## 🌍 How to View the Maps

1. Click to open in new browser 
   - https://solojh.github.io/EVChargingAnalysis/EV%20map1.html

   - https://solojh.github.io/EVChargingAnalysis/EV%20map2.html


> If the maps don't load directly on GitHub, right-click and choose **Save Link As...**, then open locally in your browser.

---
