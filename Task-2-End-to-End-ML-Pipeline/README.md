# 🔄 End-to-End ML Pipeline with Scikit-learn Pipeline API

## Objective

The objective of this project is to build a reusable and production-ready machine learning pipeline for predicting customer churn using the Telco Customer Churn dataset. The project demonstrates the complete machine learning workflow, including data preprocessing, model training, hyperparameter tuning, evaluation, and model serialization.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, billing details, contract information, and customer churn status.

---

## Methodology

1. Load and explore the dataset.
2. Handle missing values and clean the data.
3. Convert data types where necessary.
4. Perform preprocessing using Scikit-learn `Pipeline` and `ColumnTransformer`.
5. Train Logistic Regression and Random Forest models.
6. Tune hyperparameters using `GridSearchCV`.
7. Evaluate models using Accuracy, Precision, Recall, F1-score, and Classification Report.
8. Compare model performance.
9. Save the best-performing pipeline using Joblib for future predictions.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Matplotlib
* Jupyter Notebook

---

## Project Files

* `Task2_End_to_End_ML_Pipeline.ipynb`
* `customer_churn_pipeline.pkl`
* `WA_Fn-UseC_-Telco-Customer-Churn.csv`
* `requirements.txt`

---

## Results

The pipeline successfully automates data preprocessing, model training, hyperparameter optimization, and evaluation. The best-performing model is exported as a reusable pipeline for making future customer churn predictions.

---

## Future Improvements

* Add XGBoost or LightGBM models.
* Handle class imbalance using SMOTE.
* Deploy the trained pipeline using Flask or FastAPI.
* Build a simple web interface for predictions.

---

## Author

**Muhammad Bilal**

