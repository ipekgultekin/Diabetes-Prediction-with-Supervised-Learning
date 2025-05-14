# 🩺 Diabetes Prediction with Supervised Learning

This project was developed during the Akbank Machine Learning Bootcamp 2025.

## 📌 Objective
To build a machine learning model using a healthcare dataset to predict whether a person is at risk of diabetes based on health indicators.

## 📊 Dataset
- Name: Diabetes Binary Health Indicators Dataset (BRFSS 2015)
- Size: 253,680 entries × 22 features
- Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

## 🧪 Techniques Used
- Exploratory Data Analysis (EDA)
- Correlation matrix & data visualization
- Data Preprocessing (scaling, splitting)
- Logistic Regression & Random Forest Classifier
- Model evaluation using accuracy, precision, recall, and F1-score

## 📈 Results

| Model | Accuracy | Recall (Diabetes=1) | F1-score (Diabetes=1) |
|-------|----------|---------------------|------------------------|
| Logistic Regression | 0.866 | 0.17 | 0.25 |
| Random Forest | 0.860 | 0.17 | 0.25 |

> Although models achieved high overall accuracy, they struggled to correctly identify diabetic individuals due to class imbalance.

## 📌 Conclusion
This study highlights a common issue in real-world medical data: class imbalance. Future improvements might include using SMOTE for oversampling, threshold tuning, or evaluating models using ROC-AUC scores.

## 💻 Tools
- Python (Pandas, Seaborn, Scikit-learn)
- Jupyter Notebook (Kaggle)
- GitHub for version control and sharing

## 🔗 Kaggle Notebook
👉 [Click here to view the notebook](https://www.kaggle.com/code/pekgltekin/googleaihub)

