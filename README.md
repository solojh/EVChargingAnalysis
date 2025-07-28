# EV Charging Points Analysis

This project contains data analysis and visualization of electric vehicle charging points.

## File Description

- **EV map1.html**  
  Visualization Map 1 showing the locations of electric vehicle (EV) charging stations, grouped by company.

- **EV map2.html**  
  Visualization Map 2 showing the distribution by charging power.
Fast vs Slow Charging Classification
-Stations with Rated Output Power ≥ 22 kW are classified as Fast (green markers).
-Stations with Rated Output Power < 22 kW are classified as Slow (blue markers).

Marker Clustering
-All charging stations are grouped using a Marker Cluster plugin.
-When zoomed out, nearby stations are grouped together; zooming in splits them into individual points.

- **EVChargingAnalysis.ipynb**  
  Jupyter Notebook file containing the data analysis.

- **ElectricVehicleChargingPoints.csv**  
  Raw dataset of EV charging stations.

## How to View the Maps

1. Double-click `EV map1.html` and `EV map2.html` to open them directly in a web browser.  
2. If the files do not open by double-clicking, right-click and choose **Open with Browser**.

---

To regenerate the maps, run the `EVChargingAnalysis.ipynb` notebook in Jupyter Notebook.
