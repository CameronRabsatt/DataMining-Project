# Data Mining Final Project

## Overview
This project follows the CRISP-DM process for a supervised learning task.

## Problem Statement
What are the key stats and metrics that corraltae to winning in the NBA
## Dataset
- Kaggle - NBA DATASET -[ NBA_GAMES_1950_2022_.csv](https://www.kaggle.com/datasets/salikhussaini49/nba-dataset?select=NBA_GAMES_1950_2022_.csv)
- Target Variable: WL (Wins/Losses) 

## CRISP-DM Summary
- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment/Recommendation

## How to Run
Open `Cleaned_final_notebook.ipynb` in Google Colab.

## Abstract
This project analyzes NBA team performance trends starting from the 2000 season to find out which in-game statistics are most strongly related to winning games. Using a full data mining pipeline, we attempt to identify performance indicators that distinguish wins from losses and apply machine learning to represent these relations.

As per the CRISP-DM approach, we begin with domain understanding by defining the primary objective: prediction of game results (win/loss) based on team-level performance metrics such as field goal percentage, three-point shooting percentage, free throw percentage, rebounds, assists, steals, blocks, turnovers, and fouls. Data cleaning and exploration are done using Pandas and AutoViz on the dataset of over 54,000 NBA games. Data preprocessing includes categorical encoding of variables, handling missing values, and feature engineering to enhance predictive accuracy.

We use classification models with PyCaret, enabling efficient model comparison between algorithms such as Logistic Regression, Random Forest, and Gradient Boosting. After comparing models based on accuracy, precision, recall, and F1-score, a high-performing model is selected and optimized by hyperparameter tuning to improve prediction performance.

To assist in visualizing insights, we utilize Seaborn and Matplotlib to display feature distributions, win/loss relationships, and model performance results. While Explainable AI techniques such as SHAP were not utilized within this project, ensemble model feature importance plots give valuable interpretability into which metrics have the greatest influence on game outcomes.

The last analysis determines statistical drivers of success in the NBA, and the results can be informative to analysts, coaches, and fans. This student project illustrates the potential of applied machine learning in sports analytics and shows how rigorous data mining methods can uncover interesting patterns in real-world data.

