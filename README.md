# California Housing Price Analysis 

## Introduction
This is an analysis done on the California Housing Prices using the dataset. In addition to analysis,
a model has also been made to predict pricing of houses which takes into account location by ccordinates
provided 

## Analysis
While carrying out the analysis a map was also made thanks to the coordinates that had been provided as  
features in the training set. A preview of the map has been shown below with the color being a indicator of  
the price class
<img width="824" alt="Screenshot 2024-03-27 at 2 13 10 PM" src="https://github.com/shariqmalik10/California-House-Pricing/assets/25326542/272687b1-575f-47de-abfa-db02b9639ff3">

A quick look at the coorelation matrix will show that the determining factor in Median House Value is determined 
by the median income. 
<img width="802" alt="Screenshot 2024-03-27 at 2 15 53 PM" src="https://github.com/shariqmalik10/California-House-Pricing/assets/25326542/c1818f0e-e87c-4de1-96ef-dbab0f0511dc">

## Model Details 
The model made was a SVM (LinearSVR) for regression with a resulting MSE value of 0.57 (best achieving one after 
using RandomizedSearchCV to get more optimal hyperparams)
