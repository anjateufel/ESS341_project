# ESS341_project
***
This project is about detecting change of the surface before and after the wildfire of 2023 in Hawaii via cosine similarity using Sentinel-2 images and Alpha Earth AI embedded pixels. As well as detecting burned area through the Normalized Burned Ratio (NBR) using the same Sentinel-2 images and comparing the different results with one another.

***
## Data sources
***
The datasets for this project are available for download via Google Drive under this links: https://drive.google.com/drive/folders/1cnFhMAxAHG-53SUhneyHhJmdYA7DOddb.

Source for the values to categorize the severity of the fire:

Rahman, S., Chang, H.-C., Hehir, W., Magilli, C., & Tomkins, K. (2018). Inter-Comparison of Fire Severity Indices from Moderate (Modis) and Moderate-To-High Spatial Resolution (Landsat 8 & Sentinel-2A) Satellite Sensors. IGARSS 2018 - 2018 IEEE International Geoscience and Remote Sensing Symposium, 2873–2876. https://doi.org/10.1109/IGARSS.2018.8518449


***
## Setup instructions
***
The required software and all libraries are listed in the environment.yml file that can be found in the project folder.

***
## Execution Order
***
First the exact repository structure should be copied. To the folder data/raw/ add the datasets so that loading the datasets can work out seamlessly. After that the cells in the change_detection.ipynb notebook should be run in the existing order from top to bottom. The notebook can be found in the project folder under notebooks/

Repository structure:

ESS341_project/

├── README.md               
├── .gitignore              
├── environment.yml         
├── data/ 

│   ├── raw/

│   └── processed/

├── notebooks/              
└── outputs/                
