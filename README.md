# final_project_ana_tristan
Analysis of Wine Quality Data

Project Title: Predictive Analysis of Wine Quality Based on Chemical Properties
Project Category: Tabular Data
Final Project Structure:
Introduction (2 pages max.)

Brief overview of the topic:
The project aims to predict the quality ranking of wines based on their chemical properties. This is crucial for providing guidance to vineyards on the expected quality and pricing of their produce, reducing reliance on the variability of subjective wine tasting evaluations. It also empowers consumers to make informed decisions when selecting wines.
The main challenges include managing the high variability and complexity of wine data influenced by factors like grape type, fermentation, and aging processes. Developing an accurate yet interpretable predictive model suitable for vineyards and wine sellers is another key challenge.
Research questions and working hypotheses: 
# H0
The null hypothesis (H0) investigates the correlation between various features and the quality of the wine. By calculating and sorting the correlation coefficients of different variables with the 'quality' variable, we aim to identify which features have the strongest linear relationship with wine quality. 
# H1
The alternative hypothesis (H1) focuses specifically on the correlation of 'pH' and 'residual sugar' with wine quality. By examining these specific variables, we aim to understand their individual contributions and relationships to the quality of wine.
# H2
The second alternative hypothesis (H2) involves using clustering analysis to identify patterns in the data. Specifically, this hypothesis aims to determine whether there are distinct groups of wines with similar characteristics. By normalizing the selected features and applying the KMeans clustering algorithm, we can explore potential groupings within the dataset.

# Project objectives
Database Description
The dataset comprises observations on red and white wine varieties from a specific region in Portugal. The red wine dataset includes 1599 varieties, while the white wine dataset includes 4898 varieties. It covers 12 chemical properties of wines (e.g., density, acidity, alcohol content) and their quality ranking, which ranges from 1 (worst) to 10 (best). Quality ratings are derived from the median of evaluations by three independent tasters. The Model performance will be assessed using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²). Statistical tests like t-tests and F-tests will complement these metrics to evaluate the significance and reliability of the predictions.

# Descriptive statistics of the dataset
# Overview of the tables and variables
# Exploratory Data Analysis (10 pages max.)

# Detailed exploration using numerical summaries and visualizations
# Storytelling through data insights
# Discussion/Conclusions (2 pages max.)

# Key findings and take-home messages
# Implications for vineyards, wine sellers, and consumers
References

# ANNEX – Python Code

# Explanation of the steps:



#1 Import librarys

#2 Load the datasets: Load the CSV files containing wine data.
#3  View the structure of the data: Display the first few rows of the datasets for initial inspection.

#4 Descriptive statistics: Calculate and display descriptive statistics of the data.
#5 Check correlations: Calculate and display the correlation matrix between variables.
#6 Plot correlation heatmap: Visualize the correlation matrix as a heatmap.
#7 Visualize the distribution of key variables: Create histograms to visualize the distribution of variables.
#8 Scatter plots of variables most correlated with quality: Plot scatter plots to check the relationship between specific 
   variables and wine quality.
#9 Clustering Analysis: Perform PCA and KMeans clustering to identify groups of wines with similar characteristics.
#10 Regression Models (Decision Tree and Random Forest): Train and evaluate regression models to predict wine quality.
#11 Polynomial Regression: Apply polynomial regression to capture non-linear relationships between variables and wine quality.Compare the results with other models (decision tree and random forest) by visualizing the MAE values.
