# empoweringgreenmobility
Research on clean mobility, transit inequities, and EV access in Georgia


# Empowering Green Mobility: Georgia’s Transit, Equity, and Emissions Landscape

## Overview

This repository contains data, code, and visualizations from a multi-city transportation equity research project focused on **Albany**, **Savannah**, and **Atlanta**, Georgia. Originally, all files were uploaded individually as part of the research process. They have now been **organized into structured folders** to support clarity, reproducibility, and collaborative use.

## Repository Structure

| Folder | Description |
|--------|-------------|
| **Data/** | Contains raw and cleaned datasets (`.csv`, `.xlsx`) used in emissions, equity, transit, and EV infrastructure analysis. |
| **Html/** | Interactive HTML visualizations including EV equity maps, emissions layers, and transit overlays. |
| **Albany GTFS/** | GTFS transit feed files for Albany, GA (`routes.txt`, `stops.txt`, `trips.txt`, etc.). |
| **Savannah GTFS/** | GTFS transit feed files for Savannah, GA. |
| **Jpynb/** | Jupyter notebooks for all analysis, mapping workflows, and data exploration. |

> **Note:** Files originally uploaded individually are now grouped into these folders for better navigation.

---

## Research Focus

This project examines transportation inequities and clean mobility gaps across Georgia using:

- Spatial analysis of EV charging access  
- GTFS analysis of transit coverage and frequency  
- Emissions mapping using GHG datasets  
- Correlation of SVI, rent burden, income, and mobility indicators  

The goal is to identify where infrastructure and policy investments can most effectively advance **equitable clean mobility**.

---

## File Highlights

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

## Methods

Key methodologies used:

- Python-based spatial analytics (pandas, geopandas, folium)  
- GTFS parsing to evaluate transit accessibility  
- HTML map generation for interactive visualization  
- Equity-layer overlays (rent burden, income, SVI metrics)  
- Emissions mapping using publicly available environmental datasets  

---

## Contact

For questions, collaborations, or data inquiries:

**Tex Wambui**  
LinkedIn: https://www.linkedin.com/in/texwambui  
Instagram: **@SustainTheStory**


Empowering Green Mobility

Advancing Equitable Electric Vehicle Adoption in Atlanta, Albany, Savannah, and Beyond

Abstract

This white paper explores the unequal distribution of electric vehicle (EV) access and clean mobility infrastructure across Georgia. It examines the challenges underserved communities face—charging deserts, affordability, limited public transit—and offers data-driven, actionable solutions. Through geospatial mapping, policy analysis, and community insights, it calls for strategic investment and equity-centered EV policies.

Keywords

Transportation equity, EV adoption, charging deserts, disadvantaged communities, sustainability, mobility justice, infrastructure access, policy recommendations, Atlanta, Albany, Savannah

Executive Summary

While Georgia attracts major EV investments, the benefits are unevenly distributed. Wealthier communities are adopting EVs faster, while low-income and rural areas face pollution, high vehicle costs, and little infrastructure. This report reveals these gaps through spatial and socioeconomic analysis and introduces the P3 Opportunity Map—a composite tool to guide equitable investment. Key recommendations include:

Targeting charging deserts

Launching income-based EV incentives

Expanding access for renters and transit-reliant communities
With federal EV credits set to expire in 2025, urgent action is needed.

Focus Cities

Atlanta

Albany

Savannah

Comparable urban areas across the U.S.

Key Issues Explored

EV ownership gaps driven by income

Charging infrastructure deserts in urban and rural areas

Poor public transit access in car-dependent communities

Disproportionate air pollution exposure in majority-Black neighborhoods

The P3 Opportunity Map

A composite map using:

EV infrastructure data

Income and rent burden

Emissions exposure

Transit access

Vehicle ownership patterns
Used to identify high-priority zones for infrastructure investment.

Georgia Toolkit

An audit of current state tools:

Existing: NEVI funds, pilot transit programs, EV-ready codes (local only)

Missing: Used EV incentives, income-based rebates, rural EV programs, multifamily charging support

Five-Point Action Plan

Invest in Charging Equity Zones

Launch Used EV Incentives for Low-Income Drivers

Expand Multifamily Charging Infrastructure

Electrify Transit + Address First/Last Mile Gaps

Build Public-Private-Philanthropic (P3) Coalitions

Why Now?

Federal EV tax credits end in September 2025. Without state-level action, Georgia risks locking in long-term inequity in its EV transition. This project is both a roadmap and a call to act—before it’s too late.

---
References
Atlanta Department of City Planning. (2025). EV Readiness Ordinance Implementation Framework.
Centers for Disease Control and Prevention. (2021). Social Vulnerability Index (SVI). https://www.atsdr.cdc.gov/placeandhealth/svi/index.html
City of Atlanta. (2023). Office of Sustainability Annual Report.
Doustmohammadi, M. (2022). Use of the Social Vulnerability Index in investigating transit deserts. Advances in Social Sciences Research Journal, 9(6), 241–249. https://doi.org/10.14738/assrj.96.12514
Federal Transit Administration. (2023). National Transit Database (NTD) 2023: Official ridership, service area, and operational data for MARTA, Albany Transit, and Chatham Area Transit (CAT). https://content.govdelivery.com/accounts/USDOTFTA/bulletins/3be1b292
Folium Project. (2023). Folium: Python data. Leaflet.js maps [Computer software]. https://python-visualization.github.io/folium
FOX 5 Atlanta. (2024). Fewer Atlantans taking train: MARTA says numbers off. https://www.fox5atlanta.com/news/fewer-atlantans-taking-train-marta-says-numbers-off4
Georgia Department of Transportation. (2023). Georgia Transportation Infrastructure and Investment Plan.
Georgia Department of Transportation. (n.d.). Crash Data Dashboard overview. Numetric. https://support.numetric.com/en/articles/4606870-gdot-crash-data-dashboard-overview5
Internal Revenue Service. (2023). Clean Vehicle Credit: Eligibility Criteria. https://www.irs.gov/credits-deductions/individuals/clean-vehicle-credit
International Council on Clean Transportation. (2024). Electric vehicle charging at multifamily homes in the United States: Barriers, solutions, and selected equity considerations. https://theicct.org/publication/promoting-equity-ev-transition-barriers-and-solutions-to-charging-at-multi-family-homes-us-apr24/
Liu, H., Guensler, R., & Rodgers, M. (2020, June 1). Equity assessment of plug-in electric vehicle purchase incentives with a focus on Atlanta, Georgia. https://rosap.ntl.bts.gov/view/dot/49600
MARTA. (2023). Transit System Performance Reports. https://itsmarta.com
MARTA. (2025). General Transit Feed Specification (GTFS) Service Data.
National Renewable Energy Laboratory. (2025). Alternative Fuels Data Center & EVI-Pro Tool. https://www.nrel.gov/transportation/evi-pro
Texas Epidemic Public Health Institute. (2021). Social Vulnerability Index (SVI) - Texas. https://tephi.texas.gov/docs/tephi-social-vulnerability-index-report-texas.pdf?language_id=1
U.S. Census Bureau. (2023). American Community Survey 5-Year Estimates. https://www.census.gov
U.S. Census Bureau. (2023). American Community Survey 1-Year Detailed Tables: Table B08201 – Household size by vehicles available. https://data.census.gov
U.S. Census Bureau. (2024). TIGER/Line shapefiles for 2024: Georgia census tracts. https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html
U.S. Department of Energy. (2023). Alternative Fuels Data Center: Electric Vehicle Charging Station Locations. https://afdc.energy.gov
U.S. Environmental Protection Agency. (2023). Greenhouse gas emissions from a typical passenger vehicle. https://www.epa.gov/greenvehicles/greenhouse-gas-emissions-typical-passenger-vehicle
Victoria Transport Policy Institute. (2025). Evaluating transportation equity. https://www.vtpi.org/equity.pdf
Wong, M., Hernández, D., & Fitzgerald, G. (2023). Equity Assessment of Plug-In Electric Vehicle Purchase Incentives with a Focus on Atlanta, Georgia. Journal of Transport and Energy Policy, 12(1), 45–62.
Wyczalkowski, C. K., Welch, T., & Pasha, O. (2020). Inequities of transit access: The case of Atlanta, GA. Journal of Comparative Urban Law and Policy, 4(1), 657–684. https://readingroom.law.gsu.edu/jculp/vol


 

