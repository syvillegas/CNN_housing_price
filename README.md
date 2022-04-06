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

Our dataset consists of two main parts: namely, textual features about the property; and images of the properties’ exterior. This data has been obtained from the House Prices and Images - SoCal dataset, which is publicly available in Kaggle (***https://www.kaggle.com/datasets/ted8080/house-prices-and-images-socal***). To begin with, the dataset consists of more than 15 thousand real-estate properties across different cities in the United States. Each entry had 4 textual features: number of bedrooms, number of bathrooms, square footage, and name of the city. Then, in order to better predict the price of each house, the dataset provides images of the houses’ exterior, all of them with size 415x311, which were collected via web scraping.

