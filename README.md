# Module_06_Challenge : *API Challenge*

This repository contains the folder WeatherPy with the Jupyter Notebooks used for the analysis and output files. The WeatherPy.ipynb Jupyter Notebook file contains Python code, table outputs, and the linear regression analyses (following each pair of graphs) for the weather analysis. Vacation.ipynb contains Python code, table outputs, and map graphs (via hvplot) for locating hotels near cities with ideal weather conditions from the sample collected with WeatherPy.ipynb.

### Results Summary
WeatherPy.ipynb analyzes the relationships between latitude and four weather variables (maximum temperature, humidity, cloudiness, and wind speed) for a random sample of cities around the world. A moderate linear regression fit was found for maximum temperature (R<sup>2</sup>=0.676 and R<sup>2</sup>=0.542 for the northern and southern hemispheres, respectively). The linear regression fits for humidity, cloudiness, and wind speed were all very poor (each R<sup>2</sup><0.075). Thus, latitude is moderately accurate for predicting maximum temperature, but unreliable for humidity, cloudiness, and wind speed.

Vacation.ipynb locates a hotel within 10000 meters of the coordinates for cities from the WeatherPy sample with "ideal" weather conditions (temperature 20-30C, humidity 0-60%, cloudiness 0-20%, wind speed 0-3m/s). Some of these cities do not have a hotel within range.

### Relevant files:
+ VacationPy.ipynb  *(Jupyter Notebook file for map analysis)*
+ WeatherPy.ipynb  *(Jupyter Notebook file for linear regression analysis)*
+ output_data/cities.csv  *(output file of cities data retrieved from OpenWeatherMap.org API)*
+ output_data/Fig01_Lat_vs_Temp.png *(scatterplot of City Latitude vs Maximum Temperature)*
+ output_data/Fig02_Lat_vs_Humid.png *(scatterplot of City Latitude vs Humidity)*
+ output_data/Fig03_Lat_vs_Cloud.png *(scatterplot of City Latitude vs Cloudiness)*
+ output_data/Fig04_Lat_vs_Wind.png *(scatterplot of City Latitude vs Wind Speed)*
+ output_data/Fig05_LR_Lat_vs_Temp_North.png *(linear regression plot of City Latitude vs Maximum Temperature, Northern Hemisphere)*
+ output_data/Fig06_LR_Lat_vs_Temp_South.png *(linear regression plot of City Latitude vs Maximum Temperature, Southern Hemisphere)*
+ output_data/Fig07_LR_Lat_vs_Humid_North.png *(linear regression plot of City Latitude vs Humidity, Northern Hemisphere)*
+ output_data/Fig08_LR_Lat_vs_Temp_South.png *(linear regression plot of City Latitude vs Humidity, Southern Hemisphere)*
+ output_data/Fig09_LR_Lat_vs_Cloud_North.png *(linear regression plot of City Latitude vs Cloudiness, Northern Hemisphere)*
+ output_data/Fig10_LR_Lat_vs_Cloud_South.png *(linear regression plot of City Latitude vs Cloudiness, Southern Hemisphere)*
+ output_data/Fig11_LR_Lat_vs_Wind_North.png *(linear regression plot of City Latitude vs Wind Speed, Northern Hemisphere)*
+ output_data/Fig12_LR_Lat_vs_Wind_South.png *(linear regression plot of City Latitude vs Wind Speed, Southern Hemisphere)*
