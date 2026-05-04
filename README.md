# ESS341_project
***
This project is about detecting change of the surface before and after the wildfire of 2023 in Hawaii via cosine similarity using Sentinel-2 images and Alpha Earth AI embedded pixels. As well as detecting burned area through the Normalized Burned Ratio (NBR) using the same Sentinel-2 images and comparing the different results with one another.

***
## Data sources
***
The datasets for this project are available for download via Google Drive under this links: https://drive.google.com/drive/folders/1cnFhMAxAHG-53SUhneyHhJmdYA7DOddb. And you can find the datasets in this project repository under data/raw/.

***
## Setup instructions
***
The required software and all libraries are listed in the environment.yml file that can be found in the project folder.

***
## Execution Order
***
First the exact repository structure should be copied. To the folder d so that loading the datasets can work out seamlessly. After that the cells in the change_detection.ipynb notebook should be run in the existing order from top to bottom. The notebook can be found in the project folder under notebooks/

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
