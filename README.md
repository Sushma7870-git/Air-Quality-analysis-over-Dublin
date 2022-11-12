# Spatio-temporal analysis of air quality and its relationship with COVID-19 lockdown over Dublin

With the spirit of reproducible research, this repository contains codes required to produce the results in the manuscript:

> [Sushma Kumari, Avinash Chand Yadav, Manabendra Saharia, Soumyabrata Dev,Spatio-temporal analysis of air quality and its relationship with COVID-19 lockdown over Dublin,Remote Sensing Applications: Society and Environment,Volume 28,2022,100835,ISSN 2352-9385.](https://doi.org/10.1016/j.rsase.2022.100835)


Please cite the above paper if you intent to use whole/part of the code. This code is only for academic and research purposes.

## Code Organization
All codes are written in `python3`.
 
### Code
+ `AOD_data _extraction.ipynb`: Run this jupyter notebook to extract the AOD values in a given lat. long. in dataframe format.  
+ `Dublin.ipynb`: Run this file to fetch and plot NO<sub>2</sub>, SO<sub>2</sub>, CO, O<sub>3</sub>, and AOD data from Sentinel-5P, and MODIS respectively. 
+ `Dublin_TS_plots.ipynb`: Run this file for time series plots for NO<sub>2</sub>, SO<sub>2</sub>, O<sub>3</sub>, PM<sub>2.5</sub>, PM<sub>10</sub>, and AQI from ground station. 


### Results
![Alt Text](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/NO2.gif)![Alt Text](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/SO2.gif)

![Alt Text](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/CO.gif)![Alt Text](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/O3.gif)

![Alt Text](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/AOD.gif)

*Time stamps of the pollutant concentrations across the map of Dublin.*

## Time series analysis 
![](https://github.com/Sushma7870-git/Air-Quality-analysis-over-Dublin-during-Covid-19-Lockdown-using-Satellite-and-Ground-data/blob/main/charts/img.jpg?=200x300)

*Time series of the pollutant concentrations over the lockdown period.*
