# TS_Academy_Capstone_Project
## Project Overview
This project predicts Life Expectancy using a WHO dataset (2000-2015). We analyzed how health indicators like HIV/AIDS & IMMUNIZATION, and socioeconomic factors like GDP influence longevity.
## Exploratory Data Analysis
* **Distributions:** Used histograms and KDE plots to understand feature spreads.
* **Correlations:** A heatmap revealed that HIV/AIDS has a strong negative correlation with life expectancy.
* **Missing Data:** Handled via Simple Imputer.

## Modeling & Results
We compared a baseline linear model against an advanced ensemble method.

| Model | MAE | R² Score |
| :--- | :--- | :--- |
| **Linear Regression (Baseline)** | 4.26% | 0.81 |
| **Random Forest (Advanced)** | 1.7% | 0.96 |

**Conclusion:** The Random Forest significantly outperformed Linear Regression, capturing non-linear relationships that the baseline missed.
