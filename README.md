# Data Visualization Mini-Project 2

This project aims to analyze the World cup matches data from 1930 to 2014 and visualize the average number of goals scored by the home team and the away team on maps. It also includes the analysis of the heart disease prediction dataset and fitting a model to the data.

## Objective

The main objectives of this project are as follows:

1. Visualize the average number of goals scored by the away team and the home team on maps.
2. Analyze the number of matches won by the home team and the away team as the outcome of the match.
3. Determine the total number of goals scored in each match.
4. Analyze the heart disease prediction dataset.
5. Fit a model to the heart disease data and determine its coefficients and metrics.

## Data Loading

The necessary libraries for data manipulation and visualization are loaded. The WorldCupMatches.csv dataset is loaded for analysis.

## Data Cleaning and Processing

The data cleaning and processing steps include the following:

- Removing rows with empty values.
- Converting the datetime column into date and time columns with appropriate formats.
- Renaming specific column names for clarity.
- Creating a "Goals" column by adding home team goals and away team goals.
- Creating a "Match Outcome" column based on the home team and away team goals.

## Visualization of Average Number of Goals

The average number of goals scored by the away team and the home team is visualized on maps using shapefile data. The maps show the average goals scored by country.

## Analysis of Match Outcomes

The number of matches won by the home team and the away team is analyzed and visualized using a bar chart.

## Total Goals Scored Over Time

The total number of goals scored in each year from 1930 to 2014 is visualized using a bar chart to show the trend of goals scored over time.

## Heart Disease Dataset Analysis and Pre-processing

The heart disease dataset is analyzed and pre-processed. The "AHD" (heart disease diagnosis) column is converted into binary values (0 for "No" and 1 for "Yes") to prepare the target variable for model fitting. Categorical variables "ChestPain" and "Thal" are converted into numeric variables using dummy encoding.

## Model Fitting and Coefficient Plot

A logistic regression model is fitted to the heart disease data using the glm() function. The model's coefficients and summary statistics are displayed. Additionally, a coefficient plot is generated to visualize the coefficients.

