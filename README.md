
# Flood Mapping Using Google Earth Engine (GEE)

## Overview
This repository contains the code and necessary information for flood mapping using a change detection approach with Sentinel-1 SAR data in Google Earth Engine (GEE). The approach is demonstrated through a script that performs flood extent mapping, damage assessment, and population exposure analysis.

## Repository Contents
- `scripts/`: Contains the main GEE code for flood mapping (`flood_mapping.js`).
- `data/`: Contains links to datasets used in the study and optional sample data.
- `documentation/`: Contains detailed descriptions of the datasets used.

## Getting Started
### Requirements
- Access to [Google Earth Engine](https://earthengine.google.com/) with an authorized account.
- Basic knowledge of GEE JavaScript API and remote sensing.

### Running the Code
1. Open the [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
2. Copy the code from `scripts/flood_mapping.js`.
3. Set the appropriate area of interest (AOI) and parameters in the code.
4. Run the script to generate flood extent maps and related outputs.

## Datasets Used
- **Sentinel-1 SAR Data**: [Link to Sentinel-1 data](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S1_GRD)
- **JRC Global Surface Water**: [Link to JRC dataset](https://developers.google.com/earth-engine/datasets/catalog/JRC_GSW1_4_GlobalSurfaceWater)
- **WWF HydroSHEDS DEM**: [Link to DEM data](https://developers.google.com/earth-engine/datasets/catalog/WWF_HydroSHEDS_03VFDEM)
- **Global Human Settlement Population Density**: [Link to GHSL data](https://developers.google.com/earth-engine/datasets/catalog/JRC_GHSL_P2016_POP_GPW_GLOBE_V1_2015)
- **MODIS Land Cover Type Yearly Global**: [Link to MODIS Land Cover](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_Landcover_100m_Proba-V-C3_Global)

## Documentation
For more details on the data and its usage, see [data_description.md](documentation/data_description.md).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
