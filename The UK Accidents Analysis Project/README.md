
# 🛣️ The UK Accidents Analysis Project

## 📌 About the Project
This project aims to analyze road traffic accident data in the United Kingdom to understand trends over time, identify risk factors, and explore patterns in accident occurrences. Through data analysis and visualization, key insights into accident frequency, location, and conditions have been extracted.

## 📂 Dataset Used
- **Source:** UK Government Road Safety Open Data
- **Scope:** 9 years of traffic accident records
- **Features Include:** Year, accident count, weather conditions, light conditions, road surface conditions, location type (Urban/Rural), etc.

## ⚙️ Tools & Libraries
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels` (for forecasting)

## 🔍 Analysis Workflow

### 1. Data Cleaning and Preprocessing
- Handling missing values
- Encoding categorical variables (e.g., mapping Urban/Rural labels)

### 2. Exploratory Data Analysis (EDA)
- Statistical summaries of numerical variables
- Detection and visualization of outliers (Boxplots)
- Yearly trend of total accidents
- Comparison of annual accident counts in Urban vs. Rural areas

### 3. Visualizations
- Line plots for traffic flow and accident trends over years
- Analysis of factors affecting the number of accidents *(Catplots and subplots for Road Surface, Light, and Weather Conditions)*
- Forecasting the number of accidents for the coming years
- Bar charts for Urban vs. Rural accident totals
- Accident Severity Analysis

### Forecasting
- Time series forecasting using `statsmodels` (predicting next 3 years)
- Visual comparison of actual and predicted accident counts



## 📌 Conclusions
- Although the number of accidents has increased from time to time, it has generally decreased.
- Urban zones are significantly more accident-prone than Rural areas.
- Environmental and infrastructure conditions play a notable role in accident rates.
- Forecasting models provide a data-driven estimation of future accident trends.

## 📌 Notes
- The analysis is observational and does not imply causality.
- The forecasting model used is basic and can be enhanced with more complex modeling techniques.

