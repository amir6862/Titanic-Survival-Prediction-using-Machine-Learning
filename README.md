# Titanic Survival Prediction – Machine Learning Project

This project explores the classic Titanic dataset to predict passenger survival. It demonstrates a complete machine learning workflow, from data cleaning and visualization to comparing dozens of classification models.

## 🚀 Key Features

* **Comprehensive EDA:** Detailed analysis of survival rates based on passenger class, sex, and embarkation point.
* **Data Preprocessing:** Handled missing values, dropped redundant features (like `PassengerId` and `Ticket`), and performed feature engineering.
* **Automated Model Selection:** Used `LazyClassifier` to automatically train and rank 27 different machine learning models.
* **Performance Visualization:** Created clear, comparative charts for model accuracy, ROC AUC, and F1 scores.

## 📊 Technologies & Libraries

* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`, `plotly.express`
* **Machine Learning:** `scikit-learn`, `lazypredict`, `XGBoost`, `LightGBM`

## 🏆 Model Performance Results

The project compared several top-performing models. Based on the analysis, the **Support Vector Classifier (SVC)** emerged as the most accurate for this dataset:

| Model | Accuracy | Balanced Accuracy | ROC AUC | F1 Score |
| --- | --- | --- | --- | --- |
| **SVC** | **0.83** | **0.82** | **0.82** | **0.83** |
| NuSVC | 0.82 | 0.81 | 0.81 | 0.82 |
| AdaBoost | 0.81 | 0.81 | 0.81 | 0.81 |
| Logistic Regression | 0.79 | 0.77 | 0.77 | 0.78 |
| RandomForest | 0.78 | 0.78 | 0.78 | 0.78 |

## 📂 Project Structure

* `python-for-machine-learning-part-01.ipynb`: The primary Jupyter Notebook containing the data analysis and model training pipeline.

## 💡 Insights from the Data

* **Survival by Gender:** Approximately 74.2% of women survived compared to only 18.9% of men.
* **Impact of Class:** Passenger class (`Pclass`) was a significant predictor of survival probability.
