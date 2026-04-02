# Exoplanetary-classification-ML
ML model to classify exoplanet transit signals vs. false positives using TESS data and scikit-learn.

## Dataset
~2.500 observations from the TESS mission (NASA Exoplanet Archive), with the following features: Planet radius, Orbital period, Transit duration, the Planet's temperature, the magnitude of its host star, Transit depth, and the radius of its host star. 

## Methods
- Exploratory data analysis & feature engineering (log scaling, derived ratios)
- Models: HistGradientBoosting, Random Forest, SVC, Logistic Regression, KNN
- Ensembles: Voting & Stacking classifiers
- Interpretability: SHAP values

## Results
The stacking classifier achieved the best performance on the test set.
