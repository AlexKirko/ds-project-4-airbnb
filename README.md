# Installation
The code runs without issue on the standard distribution of Anaconda with Python 3.*
# Project motivation
For this project, I use Kaggle AirBnB data on [Seattle](https://www.kaggle.com/airbnb/seattle/data) and [Boston](https://www.kaggle.com/airbnb/boston) to find out how distance to city center relates to listing properties.
To be more precise, I ask and answer the following questions:
1. Do central locations in Boston and Seattle provide better anemities (beds, wi-fi, kitchen)? Are there any differences between cities? We'll use basic descriptive statistics to explore.
2. Does distance from downtown have a bigger impact on lodging price for Seattle or for Boston for AirBnB (after controlling for other variables)? We'll create another feature (distance to downtown based on the city center longitude and latitude) and build a basic supervised learning model. The goal here isn't to predict price but to look for a simple, monotone relationship between the distance to city center and listing price.
3. Do people end up happier with staying closer to downtown after controlling for other variables? We'll reuse the previous model, only now we'll use average review score as a target.
All the necessary files are included in this repository. Data files are copies of the originals from Kaggle and are used as per the Public Domain license chosen fro these data by AirBnB.
# File descriptions
* main.ipynb - the main Jupyter Notebook that includes all the logic and results
* data/boston/listings.csv - listings data for Boston
* data/seattle/listings.csv - listings data for Seattle
* data/data_uri.txt - links to the data sources
# Results
The main findings of the analysis can be found in the notebook and in a post [here](https://medium.com/@alexanderkirko/cutting-your-way-to-basic-results-through-airbnb-data-6a47b213b819).
# Licensing, Authors, Acknowledgements
You are free to use the code as you like. Kaggle data can be used as per the licnesing rules out lines here: [Seattle](hhttps://www.kaggle.com/airbnb/seattle/data) and [Boston](https://www.kaggle.com/airbnb/boston)
