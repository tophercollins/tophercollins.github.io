# Smoker Binary Prediction using Bio-Signals > [Go to project]([https://github.com/tophercollins/smoker-binary-prediction])

## Overview:
This notebook analyses the 'Binary Prediction of Smoker Status using Bio-Signals' dataset from the Kaggle Plagounded Series - Season 3, Episode 24. Link below.

https://www.kaggle.com/competitions/playground-series-s3e24/overview

### Aim:
Use binary classification to predict a patient's smoking status given information about various other health indicators.

### Evaluation Metric
Submissions are evaluated on 'area under the ROC curve' between the predicted probability and the observed target.

### Improve Data Quality

- Convert CSV data into a Pandas DataFrame.
- Remove irrelevant or unimportant data.
- Convert appropriate data into numerical format for improved usability.
- Rename columns and features for better clarity.
- Introduce new columns and features to enhance analysis.

### Observations

- Identify outliers in the data.
- Summarize key aspects of the dataset.
- Analyse trends and patterns, including revenue and student enrollments.

### Visualistions

- Create visualisations using the Matplotlib and Seaborn libraries.
- Present findings to showcase financial trends and significant insights.

### Model Creation

- Created baseline models for early predictions.
- Selected best performing models (XGBoost, Catboost, LightGBM & Random Forest) to improve through CV.
- Used best models to create a Neural Network Stacking Classifier with Scikeras's KerasClassifier and Scikit-Learn's StackingClassifier
  
### Conclusion

- Saved the cleaned and transformed data for future analysis.
- Saved the model for future use.
- Create a predictions CSV file for competition submision.
- Our final model's predictions finished with a score of 0.87583, which placed 283 out of 1910 submissions.
