# Starbucks offer prediction - Udacity Capstone Project

Udacity Data Scientist Nanodegree Capstone Project.
Overview

This is the capstone project for Udacity Data Science Nanodegree. Three simulated datasets were provided by Starbucks that were meant to evaluate the algorithm and not to mimic the behavior of real customers. The goal of project is open to be defined by students. For the purposes of this project, I defined three main goals:

1. study the impact of demographic factors and offer characteristics on the customer’s response to an offer.
2. build different models for predicting the user response to offer
3. to evaluate the accuracy, precision, recall, and F1 value of these models

# Project Results
The results showed differences across gender, income, and age lines in the completion rates. In the second part of this article, I trained and evaluated three classification models for predicting the offer response rate. Gradient Boost and SVC showed an accuracy of 77% while Random Forest had a lower accuracy rate of 73%. In terms of precision, Gradient Boost showed the highest level (74%) while the other two algorithms resulted in a 72% precision. Finally, both SVC and Gradient Boost showed an F1-score of 0.79 while Random Forest had an F1-score of 0.74.

Please find the main results in the following Medium post:

# Installation
This code runs with Python version 3. Libraries needed for running the code are:
1. scikit Learn
2. numpy
3. pandas
4. matplotlib
5. seaborn
6. json
7. tqdm
8. math

# File Description
airbnb_review_analysis.ipynb:
Notebook containing the data analysis.

listings_boston.csv:
Dataset with the Airbnb listings in the city of Boston

# Licensing, Authors, Acknowledgements
* Dataset was provided by Starbucks.
* 
