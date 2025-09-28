# Loan-Survival-Analysis-Time-to-Default-Prediction
Modeled loan repayment behavior using Kaplan-Meier and Cox Proportional Hazard models. Estimated survival probabilities over time, highlighting trends and risk exposures in loan portfolios
# Loan Survival Analysis / Time-to-Default Prediction

## Overview
This project predicts the **time until a loan defaults** using survival analysis techniques. Unlike traditional classification models, survival analysis provides **time-to-event insights**, which is highly valuable for **credit risk assessment and financial decision-making**.

The analysis leverages the **Lending Club loan dataset** (or your Credit Risk Modeling dataset) and implements **Kaplan-Meier estimators** and **Cox Proportional Hazards models** to estimate loan survival probabilities.

---

## Features
- Loan amount, term, grade, sub-grade, employment length, home ownership, interest rate, annual income, and loan purpose.
- Target: **duration until default** (`duration`) and **event observed** (`event_observed`) indicating if the loan defaulted.

---

## Key Skills Demonstrated
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature selection.
- **Survival Analysis:** Kaplan-Meier curves, Cox Proportional Hazards modeling.
- **Python Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `lifelines`.
- **Visualization:** Survival curves, hazard coefficients, borrower risk predictions.

---

## Steps Implemented
1. **Data Loading & Sampling:** Safely load dataset in Colab to prevent memory crashes.
2. **Feature Preprocessing:** Encode categorical variables and handle missing values.
3. **Survival Columns Creation:** Compute `duration` and `event_observed`.
4. **Exploratory Analysis:** Kaplan-Meier survival curves overall and by loan grade.
5. **Modeling:** Fit Cox Proportional Hazards model to estimate hazard ratios.
6. **Prediction:** Predict survival function for individual borrowers.
7. **Visualization:** Plot survival curves and model coefficients.

---

## Dataset
- **Source:** Lending Club Loan Data ([Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club))  
- **Note:** For Colab execution, the dataset is **sampled (~50k rows)** to prevent RAM issues.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Loan-Survival-Analysis.git


