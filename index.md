# Portfolio
# Detecting Corrosion on Natural Gas Pipeline Images Using CNN
## Motivation
Images of natural gas pipelines can be a source of information for pipeline reliability management in addition to existing tools. Computer vision models can be used to identify corrosion on pipelines during an inspection. They can estimate size, shape, colour, which for corrosion growth modelling. Drone with a computer vision model can lower the cost of early warning for pipelines above ground and spray coating to slow corrosion.
## Scope
3 months project to deploy a Pytorch model online to detect corrosion on natural gas pipelines.
Curated 8000 public images of pipeline and corrosion, which includes 1000 images of pipelines, 3000 corrosion and 400 images of corrosion on pipeline and 4000 of images that do not contain pipeline and corrosion, 
Processed images using PIL in RGB
Augmented image data using PyTorch, including rotation, flip, crop, hue and brightness adjustment. 
Applied cross-entropy and multi-label binary classification
## Result
Analyzed results using confusion matrix, ROC curves using sci-kit-learn. 
Achieved 94% detection accuracy on test image set. 
Deployed on Heroku. Demo:https://pipeline-corrosion-classifier.herokuapp.com
# Multivariate Analysis of Sulphur Dioxide Emission in Pulp Mill
Motivation
Sulphur dioxide emission is a regulated pollutant, and emission exceeding the limit from mill leads to a fine. Mill deploys a series of processes to scrubs sulphur dioxide from flue gas. Unexpected emission is a multifactor problem.
Scope
Identify the cause of unexpected emissions by integrating data and deploying a machine learning model.
Tasks
Collected and integrated 2327 rows and 26 features pulp mill hourly process data, including pressure, temperature, and intermediate product quality, of all equipment leading to the flue gas stack.
Reduced signal noise using auto-correlation
Adjusted cause-effect lag using cross-correlation
Applied log and box-cox transformation to skewed distribution
Data exploration using the correlation matrix
search for plant-wide oscillation using spectral analysis and spectral correlation
Split data into training and prediction set
Predicted emission using partial least square, LASSO, principle component analysis and random forest using R and Matlab. 
Compared model accuracy using R-square and RMSE
Calculate feature importance of tree-based models.
## Result
Reduced pollution fines by 10% by identifying process parameters and operating conditions that lead to emission. Provided correlation and upper limits of process parameters.
Code: Github:https://git.io/JYoE0
# Apple Stock Price Prediction
Two weeks graduate course project. Using 10k rows and six columns daily, apple stock prices
Predicted next week's price within 2% SMAPE error using decision trees and random forest models from seasonality and moving average features in Scala. 
Display result on a dashboard on Tableau.
Code: Github:https://git.io/JYogZ
# Data modelling and Integration for natural gas pipeline risk modelling
## Motivation
Pipeline operators are required by regulation to monitor and maintain pipeline reliability. This project integrates data from multiple sources, including inline inspection, report, geographical database, to predict the probability of gas service disruption and the impact on the business. The goal is to reduce risk and schedule maintenance to maximize reliability.

## Tasks
Data modelling of pipeline integrity management
Extracted transform and load data from CSV, Excel, PDF and GIS databases using Python panda to SQL server 
Created data pipeline for 100k rows and 30 columns dataset to and saved the company $80,000 in data service charge
Applied predictive corrosion model in user-defined function
Calculated the likelihood of damage to the pipeline from corrosion for each corrosion patch using Monte Carlos simulation in Python.
Quantified risk to business in dollar terms by calculating loss if service is disrupted based on population density in SQL. 
Created SQL query view tables for engineering users
# ROI of on-site solid oxide fuel cell application in hospital using process modelling
Motivation: solid oxide fuel cells are twice as efficient at converting natural gas into heat and energy as a turbine. The heat generated can be harvested for space and water heating to improve energy efficiency. This project study the return of investment of on-site application in hospital.
 See poster: Project Poster.





