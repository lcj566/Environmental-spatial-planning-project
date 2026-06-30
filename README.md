# Environmental-spatial-planning-project
GIS and remote sensing project for spatial planning analysis using CORINE, Sentinel-2, DSM, and network-based modelling in ArcGIS pro.
## Project Overview

This project presents a geospatial analysis workflow focused on spatial planning, land use assessment, environmental monitoring, and infrastructure accessibility within a selected sub-district Nakielski of the Kujawsko-Pomorskie (KP) province in Poland.



## Data Sources 
CORINE Land Cover (CLC),
Natura 2000 Protected Areas,
SRTM Digital Elevation Model (DEM),
ESRI Data & Maps,
Statistics Poland (GUS).

The objective of the project is to demonstrate how remote sensing and GIS-based analysis can support spatial planning and environmental decision-making processes.

## Study Area

Nakielski sub-district within the KP region was used as the study area. The selection was made to ensure representativeness of mixed land use conditions, including agricultural areas, forested zones, and urban settlements.

## Methodology

The workflow follows a structured geospatial analysis approach:

### 1. Administrative Selection and Spatial Context
- Selection of a representative sub-district within the KP region
- Spatial referencing and boundary definition

### 2. Land Use Analysis (CORINE Land Cover)
- Classification and quantification of land use categories
- Calculation of percentage distribution of land cover types
- Visualization of spatial land use structure

### 3. Forest Cover Analysis
- Extraction of forested areas from CORINE dataset
- Calculation of total forest cover within the study area
- Spatial representation of forest distribution patterns

### 4. Digital Surface Model (DSM) Analysis
- Clipping of DSM data to study area boundary
- Statistical analysis of elevation values
- Extraction of terrain-related characteristics relevant for spatial planning

### 5. Natura 2000 Protected Areas Analysis
- Identification and overlay of protected areas within the sub-district
- Calculation of spatial extent of conservation zones
- Assessment of overlap with other land use categories

### 6. Forest Fire Accessibility Scenario (Network Analysis)
- Identification of the largest contiguous forest complex based on CORINE data
- Determination of a central point within the forest complex (fire location scenario)
- Network analysis using road infrastructure data
- Calculation of optimal route, travel distance, and estimated travel time from the nearest State Fire Service (SFS) station

## Key Outputs
All results are compiled into a comprehensive cartographic layout:

- Land use composition (CORINE Land Cover)
- Forest cover distribution
- Digital Surface Model statistics
- Natura 2000 protected area overlay
- Emergency response route analysis for fire scenario

The final output is presented as a multi-layer GIS map layout integrating all analytical components.

## Main Deliverable

- `final_layout.png` – Comprehensive map layout containing all spatial analysis results


