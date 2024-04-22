# 202401-NBA-score-prediction


This repository presents a comprehensive Python implementation for predicting final scores of both home and away teams in basketball matches using a multivariate regression model. The model is fine-tuned through hyperparameter tuning and feature engineering, aiming to capture complex relationships between various team statistics and match outcomes.

## Overview

The provided code takes you through the entire process, from data gathering to model evaluation, offering insights and explanations at each step. The key features of this repository include:

1. **Data Collection:**
   - Utilizes the NBA API to gather team and player statistics for both home and away matches.

2. **Feature Engineering:**
   - Processes team and player statistics, calculating metrics such as win rates, average points scored, and points allowed.
   - Handles injured players and applies data weighting to enhance representation.

3. **Train/Test Data Generation:**
   - Offers an optional step to generate train/test data, involving extensive preprocessing and the removal of injured players.

4. **Multivariate Regression Model:**
   - Implements a Random Forest Regressor fine-tuned through hyperparameter tuning and feature engineering.
   - Despite logistical constraints, the model exhibits exceptional accuracy during training.

5. **Evaluation and Result Presentation:**
   - Evaluates model predictions using industry-standard metrics (MSE, R-squared).
   - Presents actual vs. predicted scores in a DataFrame for detailed comparison.

## Optional Steps

- **Train/Test Data Generation:**
   - Execute the steps in the notebook to generate train/test data for model learning.

## Notes

- I made this project before taking my Machine Learning class. It will most likely be revisted and further optimized.
- The model showcases impressive accuracy during training, with average errors as low as 6 points for home score predictions and 2 points for away scores.
- API used (needed to insert your own key): https://rapidapi.com/api-sports/api/api-nba/

## Contributions and Issues

Contributions and suggestions are welcome. If you encounter any issues or have ideas for improvement, please open an issue.

Enjoy predicting basketball match outcomes with this multivariate regression model!

