**Vegetation Indices time-series analysis using Sentinel-2 satellite imagery**
This project utilizes Google Earth Engine (GEE) to analyze Sentinel-2 satellite imagery within a specified region of interest. It calculates and visualizes Normalized Difference Vegetation Index (NDVI) and Enhanced Vegetation Index (EVI) over a defined time period. Additionally, it demonstrates exporting the calculated indices as CSV files and performing basic machine learning prediction on the NDVI time series. This code doesn't require the satellite images to download which can be run on cloud to get output and statistics in a bit which saves time and help to manage the datasets. In this code, I am using preprocessed data which doesn't require band stacking, mosaicking. If you want to download the image also later we can add the code for downloading also. After running the code, you will see the Web map where you can visualize the results and stats also. There you will get option to turn on & off the datasets for better experience in visualization.

**Setup**

To run this project, you need to have Python installed on your machine. Additionally, ensure you have the following libraries installed:

1. Earth Engine Python API
2. geemap
3. geopandas
4. pandas
5. matplotlib
You can install these libraries via pip:

**Usage**

* Authenticate Earth Engine: (You must have Google Earth Engine Account to complete authentication process, it's require code which will generated on given link in code after running the tab.)

* Run the code provided in the script Vegetation_Indices_Time-Series.ipynb. (Make sure you are using Jupyter Notebook)

* Follow the instructions in the script comments to add necessary authentication and initialize Earth Engine.

* Replace the values of START_DATE, END_DATE, and shp with your desired time period and region of interest (ROI).

* Run the script. It will display a web map showing the selected ROI and layers of NDVI, EVI, and NDVI time series.

* The script will export the calculated NDVI and EVI values as CSV files to the specified output directory.

* After exporting, the script plots the NDVI and EVI time series and performs a simple linear regression for NDVI prediction.

**Requirements**

1. Python 3.x
2. Earth Engine Python API
3. geemap
4. geopandas
5. pandas
6. matplotlib
7. Jupyter Notebook (Optional) (For best visualization of generated datasets)

   
**Credits**

This project utilizes Google Earth Engine and various Python libraries for satellite imagery analysis and visualization.
