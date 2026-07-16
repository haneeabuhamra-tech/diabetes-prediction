# Diabetes Prediction Using Machine Learning

Project Overview

This project develops and evaluates machine learning models to predict whether a patient is likely to have diabetes based on clinical and demographic data. The goal is to compare multiple classification algorithms and identify the model that provides the best predictive performance while following machine learning best practices.

Objectives

- Explore and understand the dataset through exploratory data analysis (EDA).
- Clean and preprocess the data.
- Train and compare multiple machine learning models.
- Evaluate model performance using appropriate classification metrics.
- Optimize model performance through cross-validation, pipelines, and hyperparameter tuning.

Dataset

The project uses a diabetes dataset containing patient health information. Features may include variables such as glucose level, blood pressure, BMI, insulin, age, pregnancies, and other clinical measurements. The target variable indicates whether a patient has diabetes.

Project Workflow

1. Load and inspect the dataset.
2. Perform exploratory data analysis (EDA).
3. Handle missing values and check for duplicate records.
4. Visualize feature distributions and relationships.
5. Split the data into training and testing sets.
6. Apply preprocessing techniques, including feature scaling where appropriate.
7. Train and compare multiple classification models.
8. Evaluate model performance using multiple metrics.
9. Perform cross-validation and hyperparameter tuning.
10. Interpret the results and identify the best-performing model.

Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

Evaluation Metrics

Models were assessed using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- K-Fold Cross-Validation

Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

Project Highlights

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- Machine learning pipelines
- Model comparison
- Cross-validation
- Hyperparameter tuning
- ROC curve and ROC-AUC analysis

Results

The best-performing model was selected based on its overall performance across multiple evaluation metrics rather than accuracy alone. Special consideration was given to recall and ROC-AUC because identifying patients at risk of diabetes is an important healthcare prediction task.

Future Improvements

- Explore additional ensemble models such as XGBoost and LightGBM.
- Perform feature selection and advanced feature engineering.
- Address class imbalance using resampling techniques.
- Deploy the model as an interactive web application using Streamlit or Flask.

Author

Haneen Abuhamra

Master of Medical Science | Python | Machine Learning | Healthcare Data Science
