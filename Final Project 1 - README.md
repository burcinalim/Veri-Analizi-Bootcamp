# ✈️ Airline Passenger Satisfaction Analysis

This project analyzes airline passenger satisfaction survey data to extract insights about service quality. Passengers rated 14 different service areas on a scale from 1 to 5, along with their overall satisfaction.

---

## 🔍 Project Objective

The goal of this analysis is to:

- Identify which service dimensions lead to higher or lower satisfaction,
- Create average satisfaction scores per passenger,
- Explore relationships between service features,
- Provide actionable insights based on the data.

---

## 🧮 Dataset Summary

- **Total Records:** 103,904 
- **Total Features:** 25  
- **Data Types:** Numerical and categorical  
- **Key Features:**  
  - `Inflight Service`, `Seat Comfort`, `Food and Drink`, `Cleanliness`, etc. (scores between 1–5)  
  - `Satisfaction` (Satisfied / Dissatisfied)
  - `Class`, `Type of Travel`, `Gender`, `Customer Type`, 

---

## 🔧 Analysis Steps

### 1. 🧹 Data Cleaning
- Missing values were analyzed.
- Since missing values were minimal, affected rows were excluded.

### 2. 📦 Outlier Detection
- Outliers were identified using boxplots.
- No extreme outliers were removed due to their relevance.

### 3. 🧠 Feature Engineering
- A new column, `Average_Satisfaction_Score`, was calculated by averaging the 14 individual service scores for each passenger.

### 4. 📊 Visualization
- Data was visualized using boxplots, histograms, bar charts, and heatmaps.
- Services with highest and lowest satisfaction levels were identified.

### 5. 🔗 Correlation Analysis
- Relationships between service ratings were explored via correlation matrix and heatmap.

---

## 📈 Key Findings

- **Most Satisfying Services:**  
  - Inflight Service
  - Baggage Handling
  - Seat Comfort  

- **Least Satisfying Service:**  
  - Inflight Wifi Service

- **Overall Satisfaction Score:**  
  - Average satisfaction across all passengers is approximately **3.24 / 5**

- **Strong Correlations:**  
  - `Ease of Online Booking` ↔ `Inflight Wifi Service`  
  - `Cleanliness` ↔ `Food and Drink`
  - `Cleanliness` ↔ `Seat Comfort`
  - `Cleanliness` ↔ `Inflight Entertainment`

---

## 💡 Conclusion & Recommendations

- **Inflight Wi-Fi** is a major pain point and should be prioritized for improvement.
- **Inflight Service** and **Baggage Handling** are perceived positively and should be maintained.
- Strong correlations suggest that passengers evaluate services holistically — improvements should consider the full experience.

---

## 📁 Project Files

- `Airline_Passenger_Satisfaction_Analysis.ipynb`: Main Jupyter Notebook  
- `README.md`: Project description  

---

## 🛠 Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn

---

## 📌 Notes

This project was developed as part of a data analysis bootcamp. It includes often-overlooked steps such as outlier detection, feature engineering, and detailed visual analysis to provide deeper insights.

---

## ✨ Possible Enhancements (Advanced)

- Build a machine learning model to predict passenger satisfaction.
- Compare results across different customer segments (e.g., Business vs. Economy class).
- Create an interactive dashboard using Streamlit or Dash.

---

## 👤 Author

**Burçin Alim**  
Data Analyst | Product Manager  
Email: [burcinalim1@gmail.com]  
LinkedIn: [linkedin.com/in/burcin-alim](https://www.linkedin.com/in/burcinalim1/)

