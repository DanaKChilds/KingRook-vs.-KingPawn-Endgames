# Chess Endgame Classifier: King-Rook vs. King-Pawn on A7

This project analyzes whether White can force a win in a simplified chess endgame: King + Rook vs. King + Pawn on A7. The analysis uses categorical features extracted from the UCI dataset and applies multiple classification models to evaluate predictive performance.

## Files

- `Dana Childs 756 Final Project.ipynb` — Full analysis pipeline: preprocessing, modeling, evaluation, and visualization
- `kr-vs-kp.data` — Main dataset with 3,196 rows and 36 categorical features + 1 binary target (`won` / `nowin`)
- `kr-vs-kp.names` — Feature definitions and dataset context from UCI
- `Index` — Supplementary reference material (content not used in modeling)

## Project Overview

- **Task**: Binary classification: predict whether White wins (`won`) or does not win (`nowin`)
- **Data**: All features are categorical, encoding legal board positions, threats, and control
- **Encoding**: Features encoded using `LabelEncoder` from scikit-learn
- **Target classes**: `won`, `nowin`

## Models Implemented

- Logistic Regression
- Support Vector Classifier
- Random Forest Classifier
- Principal Component Analysis (PCA) for visualization

## Evaluation Metric

- **Accuracy** (via `accuracy_score` from scikit-learn)

## Additional Methods

- **PCA** was used to project the data for visualization
- **GridSearchCV** was used to tune hyperparameters for Logistic Regression and SVC, and Randon Forest

## Data Sources

- UCI Machine Learning Repository:  
  [Chess (King-Rook vs. King-Pawn)](https://archive.ics.uci.edu/dataset/22/chess+king+rook+vs+king+pawn)

- Cited references in the notebook:
  - FBSC. (2024, September 3). *Computer Chess: A Historical Perspective*.  
    https://www.bcs.org/articles-opinion-and-research/computer-chess-a-historical-perspective/
  - Peterson, C. (2018, June 11). *The Effect of Endgame Tablebases on Modern Chess Engines*. California Polytechnic State University, San Luis Obispo.
  - Shapiro, A. D. (1987). *Structured Induction in Expert Systems*. Turing Institute Press in association with Addison-Wesley.

## Author

Dana Childs  
Final Project — 756: Applied Machine Learning
