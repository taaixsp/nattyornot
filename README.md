# **FakeOrNatty - Stock Predictions Project** 🚀📈

## 📒 **Description**
This project explores the challenge of predicting stock movements using a combination of real financial data and synthetic data augmentation techniques. The goal is to enhance model performance in the presence of class imbalance by leveraging techniques such as SMOTE (Synthetic Minority Over-sampling Technique), undersampling, and hyperparameter tuning with XGBoost.

## 🤖 **Technologies Used**
**Generative AI & Synthetic Data:** SMOTE for generating synthetic data to balance the dataset.

**Machine Learning:** XGBoost with GridSearchCV for hyperparameter tuning.

**Data & Processing:** Python (pandas, numpy, scikit-learn), Yahoo Finance API for data extraction.

**Visualization:** Matplotlib, Seaborn for analyzing performance and stock trends.

## 🧐 **Creation Process**
**Real Data Collection 📊:** Extracted historical stock prices using the Yahoo Finance API.

**Synthetic Data Generation 🤖:** Applied SMOTE to balance the dataset by generating synthetic samples for the minority class.

**Feature Engineering 🛠️:** Selected relevant features, removed unnecessary columns, and ensured correct data formatting.

**Model Training & Evaluation 🎯:** Trained an XGBoost model, performed hyperparameter tuning with GridSearchCV, and evaluated performance using precision, recall, F1-score, and confusion matrix.

## 🚀 **Results**
**Accuracy:** Improved model accuracy and recall for the minority class due to synthetic data balancing and optimized hyperparameters.

**Key Insights:** 
- SMOTE and undersampling significantly improved model fairness.

- GridSearchCV identified the best hyperparameters, optimizing learning rate, max depth, and class weighting.

- The model showed improved precision-recall tradeoff, crucial for financial applications.

**Visualization:** Confusion matrix, feature importance plots, and stock trend analysis to validate model performance.

## 💭 **Thoughts on the Project**
Building a "natty" financial dataset was challenging because markets are highly unpredictable—sometimes. This project highlights the power of synthetic data generation in handling class imbalance, especially in financial datasets where minority class predictions are crucial. The integration of SMOTE, undersampling, and hyperparameter tuning with XGBoost resulted in a more balanced and robust stock prediction model. Future improvements could involve experimenting with deep learning approaches and additional financial indicators for feature engineering.
