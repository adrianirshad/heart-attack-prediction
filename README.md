# Heart Attack Prediction

## 1. Project Overview
This project aims to predict heart attack risks using a dataset that profiles the health of individuals in Indonesia. The data covers important factors linked to cardiovascular risk, including demographics, clinical conditions, lifestyle choices, and environmental influences such as hypertension, diabetes, obesity, smoking, and pollution exposure. With heart disease on the rise in Indonesia, early detection and prevention are more important than ever. This dataset is designed to support machine learning models for predicting heart attack risks and serves as a valuable resource for public health research.

### Key Objectives:

1. Explore and analyze the demographic, clinical, and lifestyle factors in the dataset to uncover patterns and key risk factors linked to heart attacks.
2. Build and test several machine learning models to identify which model achieves the highest accuracy.
3. Perform hyperparameter tuning on the best-performing model and evaluate its performance.
4. Provide clear and actionable insights to support early intervention efforts and contribute to improved public health outcomes in Indonesia.

## 2. Data Source

The dataset used in this project contains information on individuals in Indonesia, including their demographics, clinical conditions, lifestyle choices, and environmental factors. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/ankushpanday2/heart-attack-prediction-in-indonesia).

## 3. Summary of Findings

1. **High-Risk Factors**:
     - Hypertension, high fasting blood sugar, high cholesterol levels, and obesity are strong predictors of heart attacks.
     - Lifestyle factors like smoking, alcohol consumption, unhealthy diets, and high stress levels significantly contribute to heart attack risk.

2. **Model Performance**:
     - Logistic Regression performed the best, balancing simplicity and interpretability with strong predictive power.
     - Ensemble models like Random Forest and AdaBoost also performed well but were slightly less effective than Logistic Regression.

3. **Recommendations**:
     - Focus on early detection and management of hypertension, diabetes, and high cholesterol levels.
     - Promote healthy lifestyle changes, including regular physical activity, a balanced diet, and stress management.
     - Surprisingly, those who do not smoke and consume alcohol, were the largest group of people who experienced a heart attack.
     - Target high-risk groups (e.g., individuals with a family history of heart disease or those exposed to high air pollution) for preventive interventions.

4. **Limitations**:
     - The dataset is specific to Indonesia and may not generalize to other populations.
     - Some features, like `sleep_hours`, showed no significant relationship with heart attacks and could be excluded in future analyses.
