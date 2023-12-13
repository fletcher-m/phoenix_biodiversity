# Determining BII Loss in Phoenix County
This repository has been made from content of the EDS 220 course. 

## About
This repository contains one notebook: 'phoenix-biodiversity.ipynb' that analyzes areas of Phoenix County, AZ for the amount of biodiversity, using BII as an indicator. I compare differences in BII densities between 2017 and 2020 and plot where BII has decreased.

## Visualization
After some geospatial analysis and wrangling, I find areas of Phoenix where the BII is equal to or greater than 0.75. I do this analysis for both 2017 and 2020. I then plot the differences in values between the two years.

## Highlights
 
  - Data wrangling and exploration with `pandas`
  - Geospatial data wrangling with `geopandas`
  - Accessing data from STAC catalogue
  - Plotting raster data with 'rioxarray'

## Data
The data for BII that I used came from accessing the STAC catalogue on the planetary computer. The shape files for Phoenix county can be found here: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions.

