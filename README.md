# Titanic Survival Prediction

A beginner machine learning project that predicts whether a Titanic passenger survived, using scikit-learn.

## Overview
- **Goal:** predict passenger survival from class, sex, age, family size, fare, and port of embarkation.
- **Dataset:** Titanic passenger data (loaded via `seaborn`, 891 passengers).
- **Models compared:** Logistic Regression, Decision Tree, Random Forest.
- **Tools:** Python, pandas, scikit-learn, seaborn, matplotlib, Google Colab.

## What I did
1. Explored the data and found patterns in survival by sex, class, and age.
2. Cleaned missing values and created a `family_size` feature.
3. Split the data into train and test sets (80/20, stratified).
4. Trained and compared three models using test accuracy, F1 score, and 5-fold cross-validation.
5. Analysed the best model with a confusion matrix and feature importance.

## Results
*(Replace these numbers with the ones from YOUR run of the notebook.)*

| Model | Test accuracy | Test F1 | CV accuracy |
|---|---|---|---|
| Logistic Regression | [fill in] | [fill in] | [fill in] |
| Decision Tree | [fill in] | [fill in] | [fill in] |
| Random Forest | [fill in] | [fill in] | [fill in] |

**Key takeaways:** *(2-3 sentences in your own words: best model, most important features, one limitation.)*

## How to run
1. Open `titanic_survival_prediction.ipynb` in Google Colab (or Jupyter).
2. Run all cells from top to bottom. No dataset download is needed.

## Next steps
- Hyperparameter tuning with `GridSearchCV`
- Image classification project
- Text classification project
