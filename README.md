# Capstone-Final

## Scope:
Forecast the meal delivery demand for a food delivery company. 

## Background:

For the last part of the capstone project, my task is to determine the features that are important to this dataset and forecast the food demand  
The initial data was comprised of 4 different datasets that were required to combine into one dataset.  Once the data were combined into one dataset the dataset comprised 489121 rows and 15 features.  During the data preparation, there was a test dataset without the dependent data, but after combining all the data the iterative imputer was used to fill in the dependent data.  
For more details of the features and description of the features please refer to the link below: 
https://datahack.analyticsvidhya.com/contest/genpact-machine-learning-hackathon-1/#ProblemStatement
Apart from filling the test dataset’s dependent data with the iterative imputer method, no missing data or duplicated data were found in the dataset. 
I spent most of my time understanding the data and different techniques were used to dissect the features and investigate any relationships between the features.
The dataset was split by 20% for the test and train set model and the model was analyzed by Linear Regression, DecisionTree Regression, and XGBBoost Regression models. 

## Project Conclusion:

From the regression models, better results were yielded for DecisionTree and XGB methods.  However, different feature importances were also derived from these two different models.  Following is the outcome summary:
1. The checkout price was the most important feature for DecisionTree method while the sandwich in the category feature was the most important feature for XGB.  
2. The best test and train scores were found in the XGB method (Test score:0.796, and Train 0.833).
3. The center ID 13 had the highest number of orders.
4. The city code 590 had the highest number of orders (center ID 13 was in city code 590).
5. The most ordered item is the beverages from all the food categories and followed by rice bowl.      

## Further Work:

In my mind, this project had two major components,
1. Understand the dataset in order to determine the best-performing features so resources can allocate more efficiently
2. Forecast the order behavior in the coming weeks so the cost can be managed more efficiently. 

The first task was achieved however I was unable to complete the second task due to time constraints and also it took a significant time to run the XGB method due to the size of the dataset.  This part will be completed at a later date. 
