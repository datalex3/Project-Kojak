# Project-Kojak 

## How safe is my street?: 
## Classifying images from Google Streetview to predict crime rates.

Crime rates are perceived to be linked by the appearance of a neighbothood. By referencing demogrpahic crime rates with street view images, I would like to determine what factors are correlated with higher crime rates.
While correlation is not causation, it could help reveal how the appearance of neighborhoods affects the crime rate or vice-versa.

This report could be useful for city planners and police departments to recognize red flags for criminal activity.

## DATA

The crime data is provided by a dataset from Kaggle of Seattle police department crime incidents by latitude and longitude. This data will be cross-referenced with google street view.

Example house at 47°41'05.0"N 122°21'52.8"W.

Vehicle theft.


![Image of House](https://github.com/datalex3/Project-Kojak/blob/master/googhouse.jpeg)



# Methodology

Image classification utilizing convolutional neural network to find latent features that could either classify a street as safe/not safe, or produce a probabilty of an address experiencing crime.
Locations will be referenced crime CSV file. 

# Tools

Pytorch
Google Maps API
Pixiedust
Apache Spark
