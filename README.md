# ESS341_project
***
This project is about detecting change of the surface before and after the wildfire of 2023 in Hawaii via cosine similarity using Sentinel-2 images and Alpha Earth AI embedded pixels. As well as detecting burned area through the Normalized Burned Ratio (NBR) using the same Sentinel-2 images and comparing the different results with one another.

***
## Data sources
***
The datasets for this project are available for download via Google Drive under this link: https://drive.google.com/drive/folders/1cnFhMAxAHG-53SUhneyHhJmdYA7DOddb.
* **S2_composite_202x:** Senitnel-2 imagery from 2022 or 2024 (10m resolution)
* **AEF_embedding_202x:** AlphaEarth embedded pixels from 2022 or 2024 (10m resolution)

***
## Setup instructions
***
This project was developed with Python 3.11. 
To instantly recreate the exact software environment, run the following command in your terminal:

conda env create --name SDS210_project --file environment.yml

After activate the environment: `conda activate SDS210_project`

***
## Execution Order
***
First the exact repository structure should be copied (the data folder and its subfolders must be added manually because they aren't available on GitHub). To the data/raw/ folder add the datasets. After that the cells in the "change_detection.ipynb" notebook should be run in the existing order from top to bottom. The notebook can be found in the project folder under notebooks/. All the maps for visualization and comparison that get generated when the code is run will be saved in the outputs/ folder.

Repository structure:

ESS341_project/

├── README.md               
├── .gitignore              
├── environment.yml         
├── data/ 

│   ├── raw

├── notebooks/              
└── outputs/                
