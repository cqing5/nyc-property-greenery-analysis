# Does Money Grow on Trees? Exploring the Relationship Between Urban Greenery and Property Sale Prices in New York
For my final project for CS 145 (Data Management and Data Systems), a class on the use, design, and implementation of database and data-intensive systems, my partner and I harnessed and analyzed public datasets to investigate the relationship between urban greenery (e.g., amount of trees, type of trees) and property values in New York City.

Motivated by research showing that the majority of low-income neighborhoods have less tree cover than high-income neighborhoods, we aimed to delve deeper into this potential relationship using SQL and various data visualizations. We also implemented a k-nearest neighbors (KNN) algorithm and a linear regression model to make predictions about property sale prices using tree-related data (e.g., tree density, tree species diversity). 

## Data Sources
* new_york_trees (BigQuery): Information about street trees in New York City, including data on tree species, location, condition, and other attributes
* geo_us_boundaries (BigQuery): Contains boundaries of different geospatial areas as polygons and coordinates based on the center point, including zipcodes, counties, and states
* nyc_housing [(Kaggle link)](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales): Concatenated version of the New York City Department of Finance's Rolling Sales dataset; includes information about a year's worth of property sales/transactions in New York (note that although we named this dataset nyc_housing in our project, it includes residential and non-residential properties)
