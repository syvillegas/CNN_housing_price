# Increasing predictive power of real estate hedonic pricing via CNN

Housing Prices are important economic indicators of wealth and financial well-being in an urban scenario. Most
existing automatic house price estimation systems rely only on some textual data such as the number of rooms and
floors, square footage, etc. These are important attributes that must be taken into account when pricing a property.
However, the final price is usually estimated by a human agent who visits the house and assesses it visually. It is
therefore self-evident that visual features, although difficult to quantify, are key components in the final estimation.
Predicting a houses’ prices is a very difficult task due to the heterogeneity in both the physical and the geographical
perspectives of the houses market. 

In this project, we aim to build a first draft of an automated pricing system
capable of leveraging visual information and combine it with the usual textual features. The idea is not to build a
fully operational model, given that that would require high quality data that we don’t have at our disposal. We rather
seek to build the grounds of how a potential pricing system would look like. Our approach extracts visual features
from house photographs by means of a Convolutional Neural network architecture (CNN), and then combines it with
the houses’ textual information in order to make a guess about the fair price of the property.
