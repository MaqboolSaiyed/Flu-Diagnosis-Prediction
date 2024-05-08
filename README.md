# Flu-Diagnosis-Prediction

This repository contains Python code for building a machine learning model to classify flu-like illness based on a set of symptoms.

Functionality:

-**Data Loading:** Loads data from a CSV file containing features (symptoms) and a target variable indicating the presence or absence of flu-like illness.

-**Preprocessing:** (Placeholder) Allows for custom preprocessing steps like handling missing values and converting categorical variables.

-**Model Training:** Trains three different machine learning models:
- Support Vector Machine (SVM)
- Gaussian Naive Bayes (NB)
- Random Forest Classifier (RF)

-**Evaluation:** Calculates accuracy on a held-out test set for each model.

-**Prediction Function:**
- Takes a list of symptoms (0 or 1) as input.
- Verifies the number of symptoms matches the expected features.
- Makes predictions using each trained model.
- Uses majority vote to determine the final prediction.
- Returns a dictionary containing individual model predictions and the final prediction.

**Potential Use Cases**
- Educational tool to demonstrate machine learning for medical diagnosis.
- Exploratory analysis of flu symptom patterns.

**Note:**
- This is a simplified example and should not be used for real-world medical diagnosis.
- The code includes placeholders for specific preprocessing steps based on your data characteristics.
- Consider incorporating feature engineering techniques to improve model performance.

**Getting Started**
1. Replace `'sample_flu_data.csv'` with the path to your CSV file.
2. Implement your desired preprocessing steps in the designated section.
3. Test the `predict_disease` function with your symptom data (0 or 1).

**Libraries Used**
- pandas
- numpy (optional)
- scikit-learn
- seaborn (for visualization, optional)
- matplotlib.pyplot (for visualization, optional)
- statistics (for mode)
- collections (for Counter)

**Disclaimer**
This code is provided for educational purposes only and should not be used for real-world medical diagnosis. Consult a healthcare professional for any medical concerns.