# wildfire-mitigation-report
UCSD Data Science Capstone Project \
DSC 180AB, Section B14 \
Wildfire Mitigation with SDG&amp;E

**Group Members: Gloria Kao, Shentong Li, Neil Sharma**

## Data

Due to security concerns, we are unable to share the raw datasets. Please contact Phi Ngyuen (pnguyen@sdge.com) or Kasra Mohammadi (KMohamma@sdge.com) to request access. 

There are 5 datasets used in this project:
1. `gis_weatherstation_shape_2024_10_04.csv`: Information of weather stations such as names, location, structure details, etc.
2. `src_wings_meteorology_station_summary_snapshot_2023_08_02.csv`: Meteorology data for each weather stations such as max gust and alert windspeed. 
3. `src_wings_meteorology_windspeed_snapshot_2023_08_02.csv`: Windspeed snapshots collected from weather stations, ranging from years 2012 to 2022. 
4. `src_vri_snapshot_2024_03_20.csv`: Geospatial data and risk category for the Vegetation Risk Index (VRI) polygons.
5. `dev_wings_agg_span_2024_01_01.csv`: Information of conductor spans such as location, structure details, associates weather station, etc.

Once you have the datasets, please place them all in a folder named "data" inside the root directory. The code loads the files from the `data/` directory.

## Packages

Please download the following Python packages using `pip install` so they are ready for import when you run the code. 

Basic data science packages:
- Numpy 
- Pandas

Plotting packages: 
- matplotlib.pyplot
- Seaborn

Geospatial analysis and map-drawing packages: 
- GeoPandas
- Shapely
- Folium
