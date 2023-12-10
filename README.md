# Data science project - Pollution of Cities
Authors: Sander Toma Võrk, Mark Riispapp

## Motivation & Goals 
Since our team has a common interest in nature and the future of our planet, we had an idea to investigate what countries and cities pollute our ecosystems the most. Our plan was to explore the relationships between air quality and it’s country, population, population density, gross domestic product, human development index and other attributes.  
- What parts of a country/city affect air pollution
- Clean up data and concatenate it to a big dataset with usable data
- Visualize relational data and find out correlations
- Test out models to be able to predict if a country/city has bad air quality based on different factors (gross domestic product, CO2 emissions, human development index, population)

## Getting the project running
All files are of `.ipynb` type which can be opened with Jupyter Notebook (more info on how to run notebooks [here](https://jupyter.org/try-jupyter/notebooks/?path=notebooks/Intro.ipynb)).  
  
`Data_prep.ipynb` Contains data preparation steps for city level.  
`descriptive_stats.ipynb` Contains data preparation steps for country level with some additional dynamically made graphs, to see how features change over time.  
`Generating training data.ipynb` Contains model preparation and creation made by Mark (slower).  
`Prediction_Sander.ipynb` Contains model preparation and creation made by Sander (faster) with additional correlation heatmaps.  

## Datasets
- Dataset 1 (12.5 MB): Our World in Data - Data on CO2 and Greenhouse Gas Emissions ([link](https://github.com/owid/co2-data/blob/master/owid-co2-data.csv))  
- Dataset 2 (1.9 MB): World Health Organization - Ambient outdoor air quality and health ([link](https://www.who.int/news-room/fact-sheets/detail/ambient-(outdoor)-air-quality-and-health))  
- Dataset 3 (1.7 MB): Human Development Reports - Human Development Index ([link](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI))  
- Dataset 2 (0.3 MB): United Nations - Population data by city and country ([link](http://data.un.org/Data.aspx?d=POP&f=tableCode:240))  
