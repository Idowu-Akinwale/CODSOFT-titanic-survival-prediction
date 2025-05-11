# CODSOFT-titanic-survival-prediction
# Titanic Survival Prediction

This project uses machine learning to predict passenger survival on the Titanic. It is a classic classification task based on the historical Titanic dataset and serves as an ideal beginner-friendly introduction to data science and predictive modelling.

---

## Project Overview

Using the Titanic dataset, we built and evaluated multiple machine learning models to determine whether a passenger survived based on features such as:

- Passenger class (`Pclass`)
- Sex
- Age
- Fare
- Family relationships aboard (`SibSp`, `Parch`)
- Embarkation port
- Titles extracted from names (e.g. Mr, Mrs, Miss, etc.)

The aim was to identify the most effective model and understand key features that influenced survival outcomes.

---

## Models Used

The following models were trained and compared based on accuracy:

- Logistic Regression
- K-Nearest Neighbours (KNN)
- Random Forest
- XGBoost
- LightGBM ✅ *(Best Performer)*

LightGBM achieved the highest accuracy of **84.36%**, making it the final chosen model for prediction.

---

## Key Visualisations

- **Model Accuracy Comparison** – bar chart of all models' performances
- **Confusion Matrix** – for LightGBM classification results
- **Feature Importance** – interpretation of which features most influenced survival

---

## Results Summary

- **Top Predictors of Survival**: `Title`, `Sex`, and `Pclass` played the most influential roles in predicting survival.
- **Performance**: LightGBM offered the best performance in terms of accuracy and balanced classification.
- **Interpretability**: Feature importance plots helped identify significant predictors and offer real-world insights into survival factors.

---

## Files Included

- `titanic_model.ipynb`: Main Jupyter Notebook with data cleaning, modelling, and visualisations
- `images/`: Confusion matrix, feature importance plot, and other visuals
- `dataset/`: Raw Titanic dataset

---

