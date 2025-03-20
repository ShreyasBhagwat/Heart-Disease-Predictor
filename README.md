# Heart Disease Prediction Using Machine Learning Approaches

## Project Overview

This project aims to predict heart disease using various machine learning approaches. The dataset used contains information about individuals, including age, sex, chest pain type, blood pressure, cholesterol levels, and other relevant features.

## Dataset

The dataset consists of 303 individuals and 14 columns. Here's a description of the columns:

1.  **age:** Age of the individual.
2.  **sex:** Gender (1 = male, 0 = female).
3.  **cp:** Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic).
4.  **trestbps:** Resting blood pressure (in mmHg).
5.  **chol:** Serum cholesterol (in mg/dl).
6.  **fbs:** Fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false).
7.  **restecg:** Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = left ventricular hyperthrophy).
8.  **thalach:** Maximum heart rate achieved.
9.  **exang:** Exercise-induced angina (1 = yes, 0 = no).
10. **oldpeak:** ST depression induced by exercise relative to rest.
11. **slope:** Peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping).
12. **ca:** Number of major vessels (0-3) colored by fluoroscopy.
13. **thal:** Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
14. **target:** Diagnosis of heart disease (0 = absence, 1, 2, 3, 4 = present).

## Methodology

The project involves the following steps:

1.  **Data Loading and Exploration:** Loading the dataset, exploring its structure, and performing descriptive statistics.
2.  **Data Visualization:** Creating visualizations to understand relationships between variables and identify patterns.
3.  **Data Preprocessing:** Handling missing values, if any, and scaling features.
4.  **Model Selection:** Choosing appropriate machine learning models for prediction. The models include Random Forest, Decision Tree, XGBoost, Support Vector Classifier, Logistic Regression, and K-Nearest Neighbors.
5.  **Model Training and Evaluation:** Training the selected models on the training data and evaluating their performance using accuracy, classification report, and confusion matrix.
6.  **Hyperparameter Tuning:** Fine-tuning model hyperparameters using GridSearchCV to optimize performance.

## Results

The project demonstrates the performance of various machine learning models in predicting heart disease. The results are presented in terms of accuracy, precision, recall, F1-score, and confusion matrix.

## Conclusion

This project provides insights into the application of machine learning for heart disease prediction. The results obtained suggest the potential of these models for aiding in early diagnosis and treatment.

## Usage

To run this project, you can open the Colab notebook and execute the code cells sequentially. Make sure you have the necessary libraries installed.
