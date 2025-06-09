# Carbon Footprint Estimator

This project estimates an individual's weekly carbon footprint (CO₂ kg/week) using a regression model based on lifestyle factors like diet, transport etc. It aims to raise awareness of personal environmental impact through data-driven insights.

--- 

## 📊 Dataset Used

I used a dataset from kaggle, which includes various features.Actually the assignment said to include diet, transport, and electricity usage, but I searched for many datasets and couldn't find anything like that and if I input it myself, there is a chance of making a mistake, it would have been more wrong.So I worked on the remaining features.
- **Sex**
- **Diet type**
- **Vehicle Monthly Distance Km**
  
---

## 🧠 Approach Summary

1. **Data Preprocessing**
   - Encoded categorical variables (diet type).
   - Normalized numerical inputs (transport and vehicle monthly transport).
   - Handled missing values and outliers.

2. **Modeling**
   - Implemented both Linear Regression and a Tree-Based model (Random Forest).
   - Evaluated using **Mean Squared Error (MSE)** and **visual performance plots** (e.g., actual vs predicted).

3. **Results**
   - Random forest MSE: 851671.76
     Linear Regression MSE: 619046.50
     The Linear regression model showed better performance in terms of MSE.
   - Graphs help visualize prediction accuracy and feature impact.

     ---

  ## 📦 Dependencies

  Install the required libraries using:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib

  ```bash
  pip install pandas numpy scikit-learn matplotlib

  ```






