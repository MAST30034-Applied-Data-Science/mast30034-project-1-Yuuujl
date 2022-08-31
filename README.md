# MAST30034 Project 1 README.md
- Name: Yujie Li
- Student ID: 1174055

## Instructions 
**Research Goal:** My research goal is to explore how the weather change in winter will affect taxi drivers' income by implementing Linear Regression and Random Forest Regression mdoel.

**Timeline:** The timeline for the research area is 2016-2018.

To run the pipeline, please visit the `scripts` directory and run the files in order:
1. `1.Downloading.ipynb`: This notebook downloads the raw data into the `data/raw` directory.
2. `2.Preprocessing.ipynb`: This notebook details all preprocessing steps for the yellow taxi data and outputs it to the `data/curated` directory.
3. `3.Preprocessing for weather and merge.ipynb`: This notebook details all preprocessing steps for the external weather data and merge it with processed taxi data and outputs it to the `data/curated` directory.
4. `4.Train test split.ipynb`: This notebook is used to conduct train test split for the merged data and conduct feature selection with F-test
5. `finalised model NULL Model.ipynb`: This notebook is used to construct baseline model for the analysis
6. `finalised model for LinearReg.ipynb`: This notebook is used to construct linear regression model for the analysis
7. `finalised model for RFR.ipynb`: This notebook is used to construct random forest regression model for the analysis
8. `finalised model mapping.ipynb`: This notebook is used to sketch the R-squared map aggregated by PULocationID

**Data:** Taxi data can be found in TLC website and the way to download it is provided in MAST30034 tutorial
Weather data can be found in bibliography(last page of report)
