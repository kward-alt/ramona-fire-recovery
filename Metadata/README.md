# Ramona Fire Recovery Project (2000–2020)

## 🔥🌿 Ramona Fire Recovery Project — Analysis Pipeline

```text
Ramona CDP Boundary [Notebook 02_ramona_fire_perims]
        │
        ▼
10 km Project Buffer [Notebook 02_ramona_fire_perims]
        │
        ▼
🔥 Fire Perimeters [Notebook 02_ramona_fire_perims]
   • Cedar Fire (2003)
   • Witch Creek Fire (2007)
        │
        ▼
🌿 Shrub Cover (RCMAP, 2000–2020)
        │
        ▼
🌱 Vegetation Health (NDVI, MODIS/AppEEARS)
        │
        ▼
🌡️ Climate Trends (NOAA, 1998–2025) [Notebook 01_00_ramona_climate_change]
        │
        ▼
📈 Combined Assessment:
   • Within vs. outside burn areas
   • Pre- and post-fire comparisons
   • Long-term ecological change


---

This project analyzes climate trends, vegetation health, and land-cover change in Ramona, California before and after the **2003 Cedar Fire** and **2007 Witch Creek Fire**. These two major fires formed a “ring” around Ramona and continue to shape ecological conditions today.

## Key Questions
1. **Climate Change:**  
   Has Ramona experienced long-term warming?  
   → Assessed using NOAA temperature trends (1998–2025).

2. **Vegetation Recovery:**  
   Has vegetation within the fire perimeters recovered?  
   - **Shrub Cover (RCMAP):** Compare within/outside fire boundaries.  
   - **NDVI (MODIS/AppEEARS):** Evaluate vegetation health over time.

## Data Sources
- NOAA NCEI temperature data  
- California Fire Perimeters (CAL FIRE)  
- MRLC/USGS RCMAP Shrub Cover (2000–2020)  
- NASA MODIS NDVI (AppEEARS, 2000–2020)  
- CPAD & CA Census-Designated Places for spatial boundaries

## What This Repository Contains
- Jupyter notebooks for climate analysis, shrub cover mapping, and NDVI comparison  
- Fire perimeter maps and spatial overlays  
- Data-processing workflows for long-term environmental change in Southern California chaparral ecosystems

## Purpose
To quantify how two of California’s largest wildfires reshaped the Ramona landscape and to assess whether the region shows signs of ecological recovery.

---
## [Notebook 01_00_ramona_climate_change]

🌡️ Climate Trends in Ramona, CA (1998–2025) 🌡️

Analysis of NOAA NCEI temperature records (Station: GHCND:USW00053120) shows that Ramona has experienced a clear warming trend over the past two decades. Annual maximum and minimum temperatures both increased, with:

- Maximum temperatures rising ~1.25°F per decade
- Minimum temperatures rising ~0.50°F per decade

These changes align with broader regional warming patterns observed across inland Southern California. Increasing heat, particularly higher nighttime minimum temperatures, can influence vegetation stress, soil moisture, and post-fire recovery.

The climate analysis in this project provides essential context for interpreting the NDVI and shrub-cover results. If Ramona is warming and drying over time, vegetation may struggle to regenerate at historical rates, especially in fire-affected areas. Understanding these long-term temperature shifts helps clarify whether observed vegetation changes are due to wildfire impacts, climate change, or the interaction of both.

---
## [Notebook 02_ramona_fire_perims]

🔥 Fire Perimeters: Cedar (2003) & Witch Creek (2007) 🔥

This project uses CAL FIRE's historic fire perimeter dataset to extract the two major wildfires that reshaped the Ramona region: the 2003 Cedar Fire and the 2007 Witch Creek Fire. These events collectively burned more than 300,000 acres and formed a near-complete “ring” around the town of Ramona.

Using spatial filtering and verification through fire names and alarm dates, the correct perimeters were isolated and clipped to the study area. The resulting polygons define the core regions for comparing vegetation recovery over time.

These fire boundaries are used throughout the project to:

Map the geographic extent of each fire

Compare vegetation within vs. outside burn areas

Align NDVI and shrub-cover time series with pre- and post-fire periods

Understand long-term ecological change in the Southern California chaparral biome

Together, the Cedar and Witch Creek perimeters provide the central spatial framework for analyzing how Ramona's landscape responded to two of the most significant wildfire events in California’s modern history.
