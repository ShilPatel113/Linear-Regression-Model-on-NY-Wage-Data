# Linear-Regression-Model-on-NY-Wage-Data

## Project Overview:
The core information we are interested in this project is predicting occupation's experienced wage based off of their mean wage. That is, if we know an occupation's mean wage, we want to be able to predict what their experienced wage is.

## Data Source:
The data is public data from a New York State Government database which outlines occupations and statistics revolving them. The key features are occupational roles, their mean wage, experienced wage, and location in New York State.

## Methodology:
First, I used basic data cleaning and visualization to understand the data, then split the data into train-test sets for cross-validation. After this I applied residual analysis techniques to determine if a linear model can be applied. After this I applied feature engineering to transform the response variable and reanalyzed the residuals to confirm improvements. Finally I used sklearn library's built in models to compare against the model I built.

## Tools & Libraries:
Python Coding Language, Pandas Library, Numpy Library, Sklearn Library.

## Key Findings:
All the models performed exceptionally well, so well there was nearly a perfect correlation which validates the intuitive expectation that average wage and experienced wage have statistical correlation. The primary takeaway is the fitted prediction equation which can be used to predict an occupations experienced wage given its average wage with high accuracy.

## Reproducibility:
Download the dataset into the same folder as the attached CodeAppendix notebook. Simply run the code block by block to follow the process of data reading, cleaning, analysis, improvements, reanalysis, comparisons, and results.
