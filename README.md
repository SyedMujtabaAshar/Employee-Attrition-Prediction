# Employee Attrition Prediction

This project predicts employee attrition using the IBM HR Analytics Dataset. The goal is to build a machine learning model that can predict whether an employee will leave the company based on various HR metrics and provide actionable insights for HR retention strategies.

## Table of Contents
- Project Overview
- Dataset
- Installation
- Usage
- Exploratory Data Analysis (EDA)
- Model Training
- Explainability
- HR Retention Insights
- License

## Project Overview

The project aims to:
- Predict employee attrition using machine learning classification models.
- Perform an exploratory data analysis (EDA) to uncover key factors influencing employee attrition.
- Train classification models (Random Forest and Logistic Regression) and evaluate their performance.
- Use SHAP for model explainability to interpret how various features impact predictions.
- Derive actionable insights for HR strategies to reduce attrition rates.

## Dataset

The dataset used in this project is the **IBM HR Analytics Dataset**, which has been uploaded as **"dataset"**. This dataset contains employee data such as demographic information, job performance, and other HR metrics.

The main features include:
- Demographic details (e.g., Age, Gender)
- Job satisfaction and work environment attributes
- Employee performance data
- Attrition status (Target variable: 1 for Attrition, 0 for Retention)

## Installation

To run this project, ensure that you have the required Python libraries installed. You can install them using pip.

```plaintext
pip install pandas numpy matplotlib seaborn scikit-learn shap
```

## Usage

1. Clone the repository:
   ```plaintext
   git clone https://github.com/yourusername/employee-attrition-prediction.git
   cd employee-attrition-prediction
   ```

2. Open and run the Python script or Jupyter notebook in your preferred environment.

   If using a Python script:
   ```plaintext
   python employee_attrition.py
   ```

   If using Jupyter:
   - Open the Jupyter notebook file (`employee_attrition_prediction.ipynb`).
   - Run the cells sequentially to train the model and view the results.

## Exploratory Data Analysis (EDA)

The **EDA** section includes:
- Visualization of employee attrition distribution.
- Correlation heatmap to show relationships between features.
- Distribution of key features like Job Satisfaction, Environment Satisfaction, and Age.

## Model Training

Two classification models were used:
1. **Random Forest**: A robust ensemble method for predicting employee attrition.
2. **Logistic Regression**: A simpler but effective linear model for binary classification.

The models were trained and evaluated on the IBM HR Analytics dataset, with performance metrics including accuracy, classification report, and confusion matrix.

## Explainability

To explain the model's predictions, **SHAP** (SHapley Additive exPlanations) was used:
- SHAP values for each prediction were computed.
- A summary plot was generated to highlight the most important features affecting the model's predictions.

## HR Retention Insights

Based on the trained model and SHAP analysis, actionable insights were derived for HR:
- Focus on improving employee job satisfaction, work-life balance, and compensation.
- Provide targeted interventions for employees showing high attrition risk.
- Use the model to create retention strategies tailored to specific employee demographics.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

