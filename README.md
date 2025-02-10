# Titanic Survival Prediction

This repository contains a Jupyter notebook that applies advanced machine learning techniques to predict survival on the Titanic. The project explores various classification algorithms and demonstrates the effectiveness of feature engineering and model evaluation strategies.

## Project Overview

The goal of this project is to use historical data from the Titanic passenger manifest to predict survival outcomes. Through sophisticated data preprocessing, feature engineering, and model evaluation, we uncover patterns that influenced survival, demonstrating the potential of machine learning in predictive analytics.

## Features

- **Advanced Feature Engineering**:
  - **Feature Selection**: Utilization of `SelectKBest` with `mutual_info_classif` to identify the most impactful features.
  - **Feature Explanation**: Implementation of SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) to explain the contribution of each feature to the predictions.
  - **Feature Scaling**: Application of standard scaling techniques to normalize data for optimal performance of machine learning models.

- **Exploratory Data Analysis (EDA)**: Visualization of key data points to understand demographic and survival patterns.

- **Model Selection and Training**:
  - Employ a variety of machine learning algorithms including Logistic Regression, LDA, K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Naive Bayes (NB), Decision Trees, Random Forest Classifier, Gradient Boosting, and AdaBoost.

- **Model Evaluation**:
  - **Pipeline Approach**: Integration of data preprocessing and model training within a pipeline to streamline evaluations.
  - Assessment using accuracy, precision, recall, F1-score, and ROC curves to determine model effectiveness.

## Methodology

1. **Data Collection**:
   - Data is sourced from Kaggle’s Titanic dataset.

2. **Data Preprocessing**:
   - Clean data, handle missing values, convert categories, and scale features.

3. **Feature Engineering**:
   - Select significant features and explain their relevance using advanced techniques like SHAP and LIME.

4. **Modeling**:
   - Configure pipelines for each model to ensure clean workflow from data preprocessing to model evaluation.
   - Compare a wide array of classification techniques to find the most effective models.

5. **Evaluation**:
   - Implement cross-validation within pipelines to verify model robustness.
   - Use a comprehensive set of metrics to evaluate and compare model performance.

## Future Work

- Explore more complex models and feature engineering techniques.
- Integrate additional datasets for more comprehensive insights.
- Adapt the methodology for real-time prediction models.

## Contributing

We welcome contributions in various forms:
- Model improvements and feature enhancements.
- Bug fixes and issue resolutions.
- Suggestions for documentation updates.

Please start by opening an issue to discuss substantial changes.

## License

This project is under the MIT License - see the [LICENSE](LICENSE.md) for more details.
