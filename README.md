# Housing Price Prediction – Kaggle Intro to ML

This is a basic machine learning project from Kaggle's Intro to ML course.

## Goal

Predict housing sale prices using a few selected features and a Random Forest model. The dataset and submission format come from a Kaggle learning competition meant for beginners.

## Dataset

Files used:
- `train.csv`: Training data with features + target
- `test.csv`: Test data without target
- `submission.csv`: Prediction output
- `data_description.txt`: Provided field descriptions

## Model

- Algorithm: RandomForestRegressor (Scikit-Learn, default hyperparams)
- Features used: LotArea, YearBuilt, 1stFlrSF, 2ndFlrSF, FullBath, BedroomAbvGr, TotRmsAbvGrd
- Evaluation: Mean Absolute Error (MAE)
- MAE on validation set: ~[21217.91640]

## Files

- `housing_model.ipynb`: All code, simple ML pipeline from load to submission
- `submission.csv`: Prediction file submitted to Kaggle
- `train.csv`, `test.csv`: Input datasets

## Notes

- This was a starter project. No tuning or feature engineering done.
- Used for understanding basic ML flow: load data → train → validate → predict.
- Not meant for performance or competition ranking.
