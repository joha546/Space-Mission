# Space Mission Exploratory and Data Analysis 

## Overview

This data science project focuses on exploring and analyzing space mission data, particularly satellite launches. The dataset includes information such as DateTime, Year, and launch locations specified by city and country. The primary objectives of the analysis are to identify trends, assess the success rates of space missions, and build predictive models using Logistic Regression and RandomForest Classifier.

## Dataset

The dataset used for this project contains crucial information about space missions, including launch dates, locations, and success/failure outcomes. The key columns include DateTime, Year, and launch locations specified by city and country. Additionally, data has been categorized to highlight the top 15 companies in satellite missions, and the frequency of launches is analyzed by year.

## Exploratory Data Analysis (EDA)

The EDA phase involved extracting insights from the dataset. The top 15 companies involved in satellite missions were identified. The frequency of launches was analyzed over the years, providing an overview of the space exploration landscape. Special attention was given to the Indian Space Research Organisation (ISRO), with a focus on their success rate and visualizing year-wise failed missions.

## Feature Engineering and Prediction

### Missing Values

The dataset initially contained missing values, particularly 3360 missing rocket data points. Feature engineering involved handling missing values using the SimpleImputer function from the sklearn.impute module. Unnecessary data, such as location, datum, detail, datetime, and launch site, were dropped to streamline the analysis.

### Predictive Modeling

Two machine learning models were employed for prediction: Logistic Regression and RandomForest Classifier. The RandomForest Classifier outperformed Logistic Regression, but the model's recall and F1 score were identified as areas needing improvement. The evaluation suggests that while the RandomForest model is better, there is room for enhancement to achieve a more robust predictive capability.

## Conclusion

The analysis provides valuable insights into the space mission dataset, showcasing trends, success rates, and predictive modeling. This README serves as a guide to understanding the project's objectives, methodologies, and key findings. Further refinement of predictive models and additional feature engineering could enhance the accuracy and reliability of predictions for future space missions.
