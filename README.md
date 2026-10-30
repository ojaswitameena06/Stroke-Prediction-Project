# Stroke Prediction Using Machine Learning

## 1. Project Overview

Stroke Prediction is a Predictive Analytics mini-project that uses machine learning algorithms to predict the likelihood of a stroke based on various patient health and demographic attributes.

The project analyzes patient data and builds classification models to identify patterns associated with stroke occurrence.

## 2. Objectives

- To analyze patient health and demographic information.
- To perform Exploratory Data Analysis (EDA) and identify patterns in the dataset.
- To preprocess the data for machine learning.
- To build and evaluate classification models.
- To compare model performance using different evaluation metrics.

## 3. Dataset

The project uses the **Stroke Prediction Dataset** from Kaggle.

Dataset file: `healthcare-dataset-stroke-data.csv`

The dataset contains patient information such as:

- Gender
- Age
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (Target Variable)

## 4. Technologies and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## 5. Project Workflow

1. Data Collection
2. Data Loading and Understanding
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Handling Class Imbalance using SMOTE
8. Model Training
9. Model Evaluation
10. Model Comparison

## 6. Machine Learning Algorithms

Two classification algorithms were implemented:

### Logistic Regression
A classification algorithm used to estimate the probability of stroke occurrence based on input features.

### Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees to perform classification.

## 7. Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- PR-AUC

### Performance Comparison

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 73.97% | 93.15% |
| Precision | 13.51% | 14.29% |
| Recall | 80.00% | 8.00% |
| F1-Score | 23.12% | 10.26% |
| ROC-AUC | 0.841 | 0.749 |
| PR-AUC | 0.281 | 0.133 |

## 8. Results and Conclusion

Logistic Regression achieved a recall of 80%, compared to 8% for Random Forest. It also achieved a higher ROC-AUC and PR-AUC.

Although Random Forest achieved higher accuracy, Logistic Regression performed better at identifying stroke-positive cases in this experiment.

Therefore, Logistic Regression was selected as the better-performing model based on the project's focus on identifying positive stroke cases.

The results also demonstrate the importance of evaluating multiple performance metrics, especially when working with imbalanced datasets.

## 9. Repository Contents

- `Stroke_Prediction_Mini_Project.ipynb` – Jupyter Notebook containing the complete implementation, visualizations, model training, and evaluation.
- `healthcare-dataset-stroke-data.csv` – Dataset used for the project.

## 10. Disclaimer

This project is developed for academic and educational purposes only. The predictions are experimental and should not be used for medical diagnosis or treatment decisions.

## 11. Author

Ojaswita Meena

Machine Learning | Predictive Analytics
