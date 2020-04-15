# Coursera_Capstone
## Introduction
This project is completed as part of IBM’s Data Science Professional Certificate course offered by Coursera.org. This project is about analysing the Gas stations in the Bay Area. Given the number of vehicles in the Bay Area makes it a great location for a gas station business. The Bay has n number of cities and our goal is to extract hundreds of venues along within a mile from each city. This project will look for cities where there is little or no presence of gas stations to recommend a need for gas station in those cities. Based on the analysis we would be able you recommend a city with the need to have more gas stations.

## Business Problem
The object of this project is to analyse which neighbourhood in Bay Area requires a gas station. With the help of Data Science Methodology and machine learning techniques. 

## Methodology
Analytic Approach The analytic approach for this problem is to perform unsupervised learning technique such as K-means Clustering. This will help to identify various patterns based on neighbourhoods in Bay Area.
Data Requirements We would require data such as list of Boroughs and Neighbourhood of San Francisco Bay Area, also the census data for Bay Area) 
Data Collection Once we have noted the data requirements, the next step is data collection. We need to scrape data from the online websites using libraries such as Beautiful Soup, site map. Also, using Foursquare. 
Data Understanding and Preparation The data understanding, and preparation part would be the most difficult as the collected data would not be clean. Goal here is to clean the data.
Modelling and Evaluation We would use K-Means algorithm to create K clusters. There is no such accuracy metric for Unsupervised Learning algorithm, we would use elbow graph to select the best K.


## Data Source
“https://en.wikipedia.org/wiki/List_of_cities_and_towns_in_the_San_Francisco_Bay_Area”
The San Francisco Bay Area, commonly known as the Bay Area, is a metropolitan region surrounding the San Francisco Bay estuaries in Northern California. According to the 2010 United States Census, the region has over 7.1 million inhabitants and approximately 6,900 square miles (18,000 km2) of land.The region is home to two major cities: San Francisco and Oakland and, the largest city, San Jose.

“https://foursquare.com/city-guide”
Using Foursquare to get 100 venues for each neighbourhood in Bay Area and then select only Gas Stations to build model. 
