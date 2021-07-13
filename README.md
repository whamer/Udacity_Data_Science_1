# Airbnb Open Data Analysis

## Motivation for the project

The aim of this analysis as part of the Udacity Data Science Nanodegree was to find out if it possible to suggest a suitable price per accomodation using data about the host, the location and the reviews.
Also it should be investigated what types of real estate results in the highest pricesand if the location influences the price.


## Summary of the results

It was possible to predict the prices using Random Forest algorithms but the RMSE of the prediction was only 15.68 $. The most lucrative type of real estate in the dataset are boats and there is a clear spatial connection with the price.

## Libraries used

The following python libraries are used in this project:

- pandas
- geopandas
- matplotlib.pyplot
- seaborn
- numpy
- folium
- sklearn.ensemble 
- sklearn.model_selection
- sklearn.metrics
- scipy 


## Files in the repository

- Airbnb Open Data Analysis 
	As .ipynb and as .html file containing the analysis
- ./data/Census_Block_Groups_1990/Census_Block_Groups_1990.shp
	Census Block Groups of Seattle derived from https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::census-block-groups-1990/about
- ./data/Seattle Airbnb Open Data/listings.csv
	Airbnb data of Seattle derived from https://www.kaggle.com/airbnb/seattle/data
