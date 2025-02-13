# PUBG-Game-Prediction
This repository contains a machine learning project that aims to predict the outcome of a PUBG (PlayerUnknown’s Battlegrounds) game using various player and game statistics. The model utilizes the CatBoost algorithm for its efficient handling of categorical data and its powerful performance.

# Project Overview
In the PUBG Win Prediction project, the goal is to predict the performance of players in a battle royale game based on multiple in-game features. The project involves several key stages:

# Data Wrangling
Cleaning, organizing, and preparing the dataset for analysis and model training.
Handling missing values, encoding categorical features, and splitting the data into training and test sets.

# Feature Engineering

Creating new features based on existing data to enhance model performance.
Normalizing numerical features and dropping unnecessary ones.
Example feature: total kills, combining kills from various weapons.

# Model Selection and Training

Using CatBoost, a gradient boosting model known for its speed and accuracy with categorical data.
CatBoost efficiently handles missing values and automatically encodes categorical variables, making it ideal for this dataset.

# Model Evaluation

The model's performance is evaluated using Root Mean Squared Error (RMSE), a common metric to measure prediction accuracy.

# Features

The dataset consists of 29 features, which include a combination of player statistics, game metrics, and equipment usage. Some examples of the features include:

1.Type of weapons used
2.Average headshot rate
3.Player’s group rank
4.Number of kills with different weapons
5.Player’s location on the map
6.Game time and survival rate
These features are used to train the CatBoost model, which predicts whether a player will win or lose based on their in-game data.

# Why CatBoost?
CatBoost was chosen for several reasons:

Categorical Data Handling: It can automatically process categorical data without the need for manual encoding.
Efficiency: It is known for its speed in training and for working well with large datasets.
Accuracy: CatBoost has proven success in machine learning competitions and provides strong predictive power.

# Data Wrangling
Key steps involved in data wrangling:
1.Removing irrelevant columns.
2.Handling missing data (imputation or removal).
3.Encoding categorical features (using one-hot encoding or other techniques).
4.Splitting data into training and test sets

# Feature Engineering
In this step, new features were created and existing features were transformed to make them more useful for the model. Examples include:

1.Normalization of features for better model performance.
2.Feature combinations such as total kills from various weapons.
3.Removing unnecessary features to reduce model complexity.

# Installation
To run this project, you'll need to install the following dependencies:

Python 3.x
CatBoost
Pandas
NumPy
Matplotlib
Seaborn (optional for visualization)

# Dataset 

- https://www.kaggle.com/datasets/ashishjangra27/pubg-games-dataset 
