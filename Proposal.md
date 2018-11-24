# Project-Kojak 

## Google Street View Seattle Street Tree Survey:
## Classifying Trees by Type Using Deep Learning

## Motivation

The Pacific Northwest is known for its abundance and diversity of trees. For Seattlites, urban trees are an important part of the beauty and character of the city. 
The city of Seattle spends large resources maintaining a database cataloging the locations and species of all of the cities street trees. This data is updated and verified sporadically depending on the time and resources dedicated. 
A tremendous amount of time and money could be saved by utilizing Google Street view to update and verify the database. 

## DATA

A data set of the locations of over 14,000 trees in the public right-of-way. The trees are labled by genus and species and geocoded with latitude and longitude coordinates.
The coordinates will be used to obtain Google street view images utilizing Google Maps API. 

# Methodology

Convolusional Neural Network will be trained to identify the trees in the images from the labels. 
Initially, the models will be trained to simply identify wheteher a tree is present or not.
If successful, the next stage will attempt to distinguish between very disparate tree types (such as a pine tree versus a cherry tree). 
If all is going well, a model will be developed to classify more detailed labels such as genus and possibly species.

If the model is performing poorly, other sources of data may be incorporated to aid in training. Transfer learning from tree photographs may be helpful. 
Trained models will be tested on the holdout test set. 

# Tools

Keras
Pytorch
Google Maps API
Pixiedust
Apache Spark
AWS
Pandas


# Example

"![]()"
