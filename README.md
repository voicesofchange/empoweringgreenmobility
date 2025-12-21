# Empowering Green Mobility: Georgia’s Transit, Equity, and Emissions Landscape

This repository documents a multi-city research initiative focused on transportation inequity and clean mobility infrastructure in Georgia. The project investigates public transit access, EV charging distribution, and environmental burden across Atlanta, Albany, and Savannah. All data, analysis, and media have been organized into a structured, reproducible format for public use.

---

## Project Overview

Originally developed through the Voices of Change platform as part of the E2 1 Hotels Fellowship, this research centers on:

- Gaps in electric vehicle infrastructure
- Transit access and service frequency
- Emissions exposure by neighborhood
- Socioeconomic and racial disparities in clean mobility access

The work includes geospatial mapping, policy analysis, and quantitative evaluation of service gaps and environmental burdens, with the goal of informing equitable investment strategies.

---

## Repository Structure

| Folder              | Description |
|---------------------|-------------|
| `Data/`             | Raw and cleaned datasets (`.csv`, `.xlsx`) for emissions, EV access, rent burden, and demographics |
| `Html/`             | Interactive maps including EV equity layers and emissions overlays |
| `Albany GTFS/`      | GTFS transit feed files for Albany |
| `Savannah GTFS/`    | GTFS transit feed files for Savannah |
| `Jpynb/`            | Jupyter Notebooks used for analysis and mapping |
| `visuals/`          | Slide assets and graphics used in the podcast and publications |
| `memos/`            | PDF data memos and interim reporting documents |
| `white_paper/`      | Final white paper deliverable (PDF format) |
| `podcast/`          | Audio-visual episode walkthrough with visuals |

---

## Featured Deliverables

- **White Paper**:  
  [View PDF](./white_paper/White%20Paper%20Document%20Draft.pdf)

- **Podcast Video Episode**:  
  [Watch the Visual Storyboard](./podcast/empowering_green_mobility_storyboard_video.mp4)

- **Slide Deck Storyboard**:  
  [Download Slides](./visuals/storyboard_slides.pdf)

- **Research Memos**:  
  - [Memo 1 – Overview of Equity Barriers](./memos/Memo%201.pdf)  
  - [Memo 2 – Transit Access Analysis](./memos/Memo%202%20Transportation%20Accesibility%20.pdf)  
  - [Memo – Emissions Patterns](./memos/Memo%201%20Emissions%20Report.pdf)

---

## Research Focus Areas

This project explores spatial and structural inequities in Georgia’s clean mobility infrastructure. Methods and findings include:

- Mapping disparities in EV charging infrastructure using DOE and AFDC data  
- GTFS-based transit frequency and coverage analysis in all three cities  
- Social vulnerability overlays with emissions distribution by tract  
- Intersectional assessment of race, rent burden, poverty, and vehicle access  

---

## Methods Summary

- Python-based geospatial analysis (`pandas`, `geopandas`, `folium`)
- Transit service evaluation using GTFS feed parsing
- Interactive map development (Leaflet.js + Folium)
- Composite scoring via P3 Opportunity Map:
  - Pollution (emissions per capita)
  - Poverty (income, rent burden)
  - Public transit gaps (coverage and service area)

---

## File Highlights

### Data/
- `alt_fuel_stations_ev_charging_units.csv`
- `Transit Authorities in Georgia (Rates).csv`
- `GHG_emissions_by_econ_sector.xlsx`

### Html/
- `atlanta_ev_equity_map_with_income_rent.html`
- `savannah_emissions_map.html`

### GTFS Folders
- `routes.txt`, `stops.txt`, `trips.txt`, `calendar.txt`, `fare_attributes.txt`

### Jpynb/
- `egm_code.ipynb` — EV access + emissions modeling  
- `Atlanta_Savannah.ipynb` — Cross-city transit and emissions comparison  

---

## Policy Recommendations

The white paper outlines five key recommendations based on data findings:

1. Invest in Charging Equity Zones  
2. Expand Used EV Incentive Access for Low-Income Drivers  
3. Support Multifamily and Renter-Focused Charging Infrastructure  
4. Electrify Transit Fleets and Address First/Last Mile Gaps  
5. Build Cross-Sector P3 Coalitions to Scale Infrastructure Responsibly  

These recommendations are grounded in both the quantitative outputs and spatial analysis documented in this repository.

---

## Why This Work Matters

Georgia is attracting significant electric vehicle manufacturing investment. Without equity-oriented planning, there is a risk that historically underserved communities will remain excluded from this clean mobility transition.

This project provides a data-backed roadmap to inform strategic investment, community-centered infrastructure development, and future research across urban and rural contexts.

---

## Citation

If referencing this repository or the Empowering Green Mobility research project in academic or policy work, please cite the final white paper PDF located in the `white_paper/` directory.

---
