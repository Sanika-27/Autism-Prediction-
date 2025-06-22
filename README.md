Autism Spectrum Disorder (ASD) Prediction using Machine Learning

This project focuses on building a machine learning-based classification model to predict the likelihood of Autism Spectrum Disorder (ASD) in individuals based on behavioral and demographic features.

## 📊 Dataset
The dataset (`train.csv`) includes a mix of categorical and numerical features such as:
- Ethnicity
- Relation
- Age
- Behavioral screening results
- ASD class labels (yes/no)

## 🧪 ML Algorithms Used
- Support Vector Machine (SVM)
- Logistic Regression
- XGBoost Classifier

## 🔧 Preprocessing Steps
- Handling missing values and ambiguous entries
- Label encoding of categorical features
- Standardization using `StandardScaler`
- Class balancing using `RandomOverSampler` from `imblearn`

## 📈 Evaluation
Model performance is evaluated using accuracy, confusion matrix, and other relevant metrics from `sklearn.metrics`.

## 🖼️ Visualizations
- Class distribution pie chart
- Exploratory data analysis (EDA) using `seaborn` and `matplotlib`

## ⚙️ Libraries Used
- pandas, numpy
- scikit-learn
- xgboost
- imbalanced-learn (`imblearn`)
- seaborn, matplotlib


