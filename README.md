# spatial-distribution-post-fire-soil-losses
This is the project that corresponds the manuscript authored by Ana Novo, Cristina Fernández, Clara Míguez, and Estefanía Suárez-Vidal, submitted to Ecological Informatics and waiting for review. The project uses Sentinel-2 images and fire severity field data to map the spatial distribution and estimate potential soil losses. 

Field surveys were carried out as soon as it was possible to enter the burned areas, with 250 out of a total of 50 plots established. The field data were collected on the following dates: for the Folgoso do Courel and Carballeda de Valdeorras wildfires, from July 28th 252 to August 4 th (17 days after the fire) and for the Sierra de la Culebra wildfire, from July 2th 253 to July 4 th 254 (13 days after the fire). The classification of soil fire severity levels, based on visual indicators of soil organic cover and mineral soil disturbance. A total of 50 areas were selected where vegetation severity was particularly high, and tree canopies were charred.
Sentinel-2 images were selected over the study areas on three different dates: pre-fire (within 20 days before the fire ignition), during field sampling (within 8 days after the fire ignition), and post-fire (within 35 days after the fire ignition). The images were downloaded from the Copernicus Data Space website (https://dataspace.copernicus.eu/) The selection process ensured limited cloud cover.
Firstly, the next indices were analyzed: Normalized Burned Ratio (NBR), Normalized Difference Infrared Index (NDII), the Normalized Wildfire Ash Index (NWAI), and Blue Normalized Vegetation Index (BNDVI). Then, Soil erosion (Mg ha-1 346) was calculated for each field sample point based on soil burn 347 severity, annual precipitation (mm), and the land use factor. Finally, the spatial distribution map of potential soil losses was generated selecting the high severity burned areas and establishing regression equations of BNDVI index and estimated soil losses in these areas.

# What you can find in each folder
- **Data**: 
This folder contains the data I used to calculate potential soil losses, including:
  Indices
  Sentinel-2 imagery
  Field data
- **Results**: 
This folder contains the index selected to calculate the potential soil losses, of wildfire perimeter and the potential soil losses layers.

- **Final data**: 
This document contains the results where the field points contain each calculated index.

# Download:  

Dataset can be download at [Download] (https://1drv.ms/f/c/066fb5abf22cb08d/EnuYUhS9LI5Gtb8J6JPhrN4BGvFNNjdC0tOb1-8DmM0wLg?e=Hat6Ty) 
