## Internship FrieslandCampina
This repo contains three notebooks written during an internship at FrieslandCampina. These notebooks are alterd, the file paths are removed and how some dataframes are created.

### Author: Marijke Eggink
### Date: 21-6-2022

## Overview
These notebooks are written in databricks notebooks, except for EDA_potassium.ipynb. This notebook is written in jupyter notebook in dataiku. 

The notebook EDA_potassium.ipynb contains an exploratory data analyisis that explores which features have correlation with the potassium levels.
The datasets used in this noteboook are the quality data and weather data from the KNMI.

The notebook potassium_model.ipynb contains the training,testing and validation of the created machine learning model that predicts what the potassium levels will be.
In this notebook only the qulity data is used.

The notebook landing_to_curated.ipynb reads multiple csv files in from the landing storage layer and writes this data to a delta table in the curated storage layer. This notebook receives three parameters: type (sensor data or metadata), factory (which factory), folder (batch or backfill).