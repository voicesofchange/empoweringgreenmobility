# empoweringgreenmobility
Research on clean mobility, transit inequities, and EV access in Georgia


# Empowering Green Mobility: Georgia’s Transit, Equity, and Emissions Landscape

## 📌 Overview

This repository contains data, code, and visualizations from a multi-city transportation equity research project focused on **Albany**, **Savannah**, and **Atlanta**, Georgia. Originally, all files were uploaded individually as part of the research process. They have now been **organized into structured folders** to support clarity, reproducibility, and collaborative use.

## 🗂️ Repository Structure

| Folder | Description |
|--------|-------------|
| **Data/** | Contains raw and cleaned datasets (`.csv`, `.xlsx`) used in emissions, equity, transit, and EV infrastructure analysis. |
| **Html/** | Interactive HTML visualizations including EV equity maps, emissions layers, and transit overlays. |
| **Albany GTFS/** | GTFS transit feed files for Albany, GA (`routes.txt`, `stops.txt`, `trips.txt`, etc.). |
| **Savannah GTFS/** | GTFS transit feed files for Savannah, GA. |
| **Jpynb/** | Jupyter notebooks for all analysis, mapping workflows, and data exploration. |

> **Note:** Files originally uploaded individually are now grouped into these folders for better navigation.

---

## 🧪 Research Focus

This project examines transportation inequities and clean mobility gaps across Georgia using:

- 📍 Spatial analysis of EV charging access  
- 🚌 GTFS analysis of transit coverage and frequency  
- 🌍 Emissions mapping using GHG datasets  
- 📊 Correlation of SVI, rent burden, income, and mobility indicators  

The goal is to identify where infrastructure and policy investments can most effectively advance **equitable clean mobility**.

---

## 📂 File Highlights

### **Data/**
- `alt_fuel_stations_ev_charging_units.csv` — Alternative fuel and EV charging unit dataset  
- `Transit Authorities in Georgia (Rates).csv` — Transit fare structures  
- `GHG_emissions_by_econ_sector.xlsx` — Emissions by economic sector  
- `vehicle_history.xlsx`, `afv_disp_history.xlsx` — Vehicle and fuel displacement records  

### **Html/**
- `atlanta_ev_equity_map_with_transit.html` — Atlanta EV and transit overlay  
- `atlanta_ev_equity_map_with_income_rent.html` — Atlanta income/rent + EV access  
- `savannah_emissions_map.html` — Savannah emissions visualization  
- `atlanta_emissions_map.html` — Atlanta emissions visualization  

### **Albany GTFS/** & **Savannah GTFS/**
Files include:
- `routes.txt`
- `stops.txt`
- `trips.txt`
- `stop_times.txt`
- `calendar.txt`
- `fare_attributes.txt`
  
Used to reconstruct transit network geometry and analyze coverage and frequency.

### **Jpynb/**
- `egm_code.ipynb` — Full data cleaning, mapping, EV access analysis  
- `Atlanta_Savannah.ipynb` — Cross-city emissions and transit comparison  

---

## 🔍 Methods

Key methodologies used:

- Python-based spatial analytics (pandas, geopandas, folium)  
- GTFS parsing to evaluate transit accessibility  
- HTML map generation for interactive visualization  
- Equity-layer overlays (rent burden, income, SVI metrics)  
- Emissions mapping using publicly available environmental datasets  

---

## 📬 Contact

For questions, collaborations, or data inquiries:

**Tex Wambui**  
LinkedIn: https://www.linkedin.com/in/texwambui  
Instagram: **@SustainTheStory**

---

 

