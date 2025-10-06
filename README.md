# 📊 Datathon-MTA: ACE Violations & Bus Route Analysis

## Overview
Analyzes NYC bus routes near CUNY campuses to assess ACE enforcement impact, route popularity, and spatial violation patterns.

## Goals
- Match ACE routes to CUNY stops  
- Visualize customer usage and violation types  
- Track monthly ACE violations (e.g., BX19)  
- Map speed variability and repeat offenders  

## Data Sources
- NYC Open Data (routes, violations, speeds, ACE)  
- Manually curated CUNY campus coordinates  

## Methods
- Geopy for proximity analysis  
- Cleaned and merged datasets  
- Visuals: pie charts, time series, Folium maps  
- Stats: speed deviation, violation clustering  

## Key Findings
- **BX19** shows high usage and ACE violations  
- **SOUTHERN BLVD/E 163 ST** is a congestion hotspot  
- Repeat violations concentrated in few locations  

## Next Steps
- Add delay and fare equity metrics  
- Build interactive dashboards  
- Explore causal links between ACE and performance  

## Setup
```bash
pip install pandas geopy matplotlib folium
