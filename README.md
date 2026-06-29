# nba_feature_engineering
Machine learning project predicting whether NBA rookies will play for at least five years.
# Project Overview
This project develops a machine learning model to predict whether an NBA rookie will remain in the league for at least five years based on their rookie season statistics.
The project covers the complete machine learning workflow, including data preprocessing, feature engineering, exploratory data analysis, model training, evaluation, and feature importance analysis.

# Dataset
The dataset contains NBA rookie statistics, including variables such as:
Games Played (GP),
Minutes Played (MIN),
Points (PTS),
Field Goals Made (FGM),
Field Goal Attempts (FGA),
Free Throws Made (FTM),
Free Throw Attempts (FTA),
Offensive Rebounds (OREB),
Defensive Rebounds (DREB),
Assists (AST),
Steals (STL),
Blocks (BLK),
Turnovers (TOV),

Target Variable
  target_5yrs
  1 = Player remained in the NBA for at least 5 years
  0 = Player did not remain in the NBA for at least 5 year

  # Feature Engineering
New features were created to provide more meaningful performance indicators, including:
Points Per Minute
These engineered features help the model capture player efficiency beyond raw statistics.

# Project Workflow
Load the dataset,
Explore the data,
Handle missing values,
Feature engineering,
Feature selection,
Feature importance analysis.

# Tools Used
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook.

