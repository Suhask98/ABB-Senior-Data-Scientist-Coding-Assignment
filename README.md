This repository contains my solution for the ABB Senior Data Scientist Coding Assignment.
The goal was to build a predictive model on the provided dataset and submit predictions on the test set.
The final evaluation metric was Root Mean Squared Error (RMSE), and leaderboard ranking was based on this score


Approach Summary:
1) Exploratory Data Analysis (EDA): Understood distribution, handled missing values and data discrepancies.

2) Feature Engineering: Applied transformations (interaction terms) and encoding for categorical features (label encoding).

3) Modeling & Hyperparameter Tuning: Experimented with multiple models such as XGBoost, CatBoost, and random forests.

4) Used Optuna for hyperparameter optimization.

5) Final Model Selection: Chose the best-performing model based on cross-validation RMSE (fine-tuned Catboost).

6) Submission: Generated predictions for the test dataset and prepared the final submission file.

Results: <br>
Best RMSE Score: 1016.436 <br>
Leaderboard Rank: 1
