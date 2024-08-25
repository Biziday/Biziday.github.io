---
layout: post
author: Name
title: "Applied Data Science Project Documentation"
categories: ITD214
---
## Project Background
The project's primary objective is to empower married couples in Singapore by providing predictive insights into HDB resale prices. This would enable them to make informed decisions and strategic plans concerning their property investments, considering the continuously rising costs of HDB flats.

## Work Accomplished
Document work done to accomplish the outcome

### Data Preparation
Random Forest
Data Cleaning and Transformation: The dataset was cleaned by handling missing values, such as dropping the 'remaining_lease' column due to missing data. Additional features were engineered from existing columns, including extracting 'year' from the 'month' column and defining price categories (low, medium, high).
Normalization: Numerical features were standardized to prepare them for modeling, ensuring they were on a comparable scale for the Random Forest Classifier.

### Modelling
Random Forest Classifier was chosen to classify HDB flats into three price categories (low, medium, high). The model was trained using the training data, with hyperparameters tuned to improve performance.
The model's performance was assessed using a classification report and accuracy scores, demonstrating its ability to categorize flats effectively based on the pre-defined criteria.

### Evaluation
Random Forest
The Random Forest model was evaluated based on its classification accuracy and its ability to provide clear predictions on HDB resale price categories. The evaluation metrics indicated a high level of accuracy and reliability in predictions.

## Recommendation and Analysis
Recommendations for married couples based on the model's findings.
Affordability Assessment: Couples can use the model to determine which HDB flats fall into low, medium, or high price categories based on their budget.
Location Considerations: Analysis of average resale prices in different towns helps identify more affordable areas.
Flat Type Analysis: Evaluation of different flat types to find the best fit for budget and needs, with smaller flats often being more affordable.

## AI Ethics
Ethical considerations would include ensuring unbiased predictions, protecting user data privacy, and maintaining transparency in model usage and recommendations.
## Source Codes and Datasets
Upload your model files and dataset into a GitHub repo and add the link here. 
https://github.com/Biziday/itd214_project
