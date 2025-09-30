# ML-Competition-Titanic-Dataset
This repository contains a complete machine learning pipeline for the Titanic: Machine Learning from Disaster competition. It’s designed to be step-by-step, well-documented, and beginner-friendly, while also incorporating advanced techniques for robust model performance.

Features & Highlights:

- Full Exploratory Data Analysis (EDA): Includes missing-value checks, distribution plots, correlations, and insights to understand the dataset.
- Robust Feature Engineering: Derived features like Title, Deck, FamilySize, FarePerPerson, and bins for Age/Fare to improve model predictive power.
- Smart Imputation: Missing values are handled using group medians with fallback strategies for consistent data quality.
- Encoding & Column Alignment: Proper encoding of categorical variables and alignment of train/test columns for smooth modeling.
- Stratified K-Fold Training: Implemented for XGBoost, LightGBM, and CatBoost with out-of-fold (OOF) probabilities to ensure robust cross-validation.
- Blending & Stacking: Combines model predictions using averaging and a Logistic Regression meta-model for improved final predictions.
- Submission Generation: Generates submission_stacked.csv ready for Kaggle submission.
