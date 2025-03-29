# Perth House Price Prediction 

## Overview
This repository contains a comprehensive econometric modeling and statistical forecasting project conducted as part of the **ECOM5002: Business Quantitative Analysis** unit at Curtin University. The project involved building predictive models for residential house prices in **three Perth suburbs**: Inglewood, Dunsborough, and Bull Creek.

Leveraging **R programming**, we applied statistical techniques including descriptive analysis, correlation, multiple regression, confidence intervals, and model reduction to forecast the market price of advertised properties and evaluate the prediction against ANZ forecasts.

---

## Objectives
- Analyze property data from realestate.com.au
- Clean and prepare data for regression modeling
- Build multiple and reduced form linear regression models
- Estimate confidence intervals for slope coefficients
- Predict prices of real-world listings and validate against ANZ forecasts

---

## Methodology
1. **Data Collection:**
   - 150 recent property sales across 3 suburbs (50 per suburb)
   - Attributes: Price, Land Size, Bedrooms, Bathrooms, Car Ports, Age, School Proximity

2. **Data Cleaning:**
   - Removal of anomalies and incomplete records
   - Creation of dummy variables for categorical fields (suburb)

3. **Statistical Analysis:**
   - Descriptive statistics: mean, median, variance, standard deviation
   - Visualizations: histograms, scatterplots, boxplots
   - Confidence intervals (90% for Price & Age, 95% for slopes)

4. **Modeling in R:**
   - Full regression model with all variables
   - Reduced model based on significance (p-values)
   - Prediction using `predict()` function

5. **Model Validation:**
   - Comparison with ANZ market forecast
   - Accuracy measured by deviation from midpoint estimate

---

## Key Results
- Developed a reduced regression model with an **adjusted R² ≈ 35.77%**
- Achieved **~80.5% prediction accuracy** on real listing vs. ANZ forecast
- Identified significant predictors: land size, no. of bathrooms, school proximity, suburb

---

## File Structure
| File | Description |
|------|-------------|
| `Group12_Report.pdf` | Final analytical report including data, methods, results, and evaluation |
| `Group12_Code.Rmd` | R Markdown code for complete analysis and model creation |
| `Datafile.csv` | Cleaned dataset of 150 residential properties |
| `Assessment 1 brief.docx` | Assignment guidelines and expectations |

---

## Technologies Used
- **Language**: R
- **Packages**: `ggplot2`, `dplyr`, `readr`, `lm`, `summary()`, `predict()`
- **Techniques**: Regression, ANOVA, Confidence Intervals, Visual Analysis

---

## Authors
**Group 12 – Curtin University (ECOM5002)**  
- Syed Muhammad Ahmed Zaidi (20972008)  
- Mohammad Adil Jan Malik (21320394)  
- Umair Sattar (21361924)

---

## License
For academic use only. © Curtin University – Business School, 2023.

---
