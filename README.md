# 🏠 House Price Correlation Analysis

## 📌 Project Overview

This project analyzes the relationship between house features and house prices using correlation analysis. The goal is to identify the most influential variables affecting property prices and derive meaningful business insights for real estate pricing strategy and predictive modeling.

---

## 🎯 Objective

* Identify the most correlated variables with house price
* Understand relationships between features
* Select important variables for price estimation
* Provide business insights from data

---

## 📂 Dataset Description

The dataset contains the following features:

```
id, date, price, bedrooms, bathrooms, sqft_living, sqft_lot,
floors, waterfront, view, condition, grade,
sqft_above, sqft_basement, yr_built, yr_renovated,
zipcode, lat, long, sqft_living15, sqft_lot15
```

Target Variable: **price**

---

## 🛠 Tools & Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Jupyter Notebook

---

## 🔎 Data Preprocessing

* Removed irrelevant columns: `id`, `date`
* Checked for missing values
* Generated correlation matrix
* Visualized correlation heatmap

---

## 📊 Correlation Analysis

A heatmap was generated to analyze relationships between numerical variables.

### 🔝 Strong Positive Correlations with Price

| Feature       | Insight                                          |
| ------------- | ------------------------------------------------ |
| sqft_living   | Strongest predictor of price                     |
| grade         | Construction quality significantly impacts price |
| sqft_above    | Above-ground living space affects value          |
| bathrooms     | More bathrooms increase property value           |
| sqft_living15 | Neighborhood living area impacts price           |
| view          | Better view increases desirability               |
| waterfront    | Waterfront properties command higher price       |

---

## 📉 Weak Correlations

| Feature   | Observation                                               |
| --------- | --------------------------------------------------------- |
| sqft_lot  | Large land size does not strongly impact price            |
| bedrooms  | Bedroom count alone does not increase price significantly |
| condition | Weak influence compared to grade                          |
| yr_built  | Age has limited direct impact                             |

---

## 🧠 Key Insights

1. Living space is the strongest driver of house price.
2. Construction quality (grade) significantly influences valuation.
3. Buyers prioritize interior usable space over lot size.
4. Location factors like waterfront and view add premium value.
5. Bedroom count is less important compared to total living area.

---

## 📌 Variables Recommended for Price Estimation

### ✅ Strong Predictors

* sqft_living
* grade
* sqft_above
* bathrooms
* sqft_living15
* view
* waterfront

### ⚠ Moderate Predictors

* floors
* yr_built
* lat
* condition

### ❌ Not Recommended

* id
* date
* sqft_lot
* sqft_lot15

---

## 📈 Business Impact

This analysis helps:

* Real estate companies improve property pricing models
* Analysts build better regression models
* Agents focus marketing on high-value features
* Investors identify value-driving attributes

---

## 🚀 Future Improvements

* Build Linear Regression model
* Perform Feature Engineering
* Apply Regularization (Ridge/Lasso)
* Compare ML models
* Create interactive dashboard

---

## 📌 Conclusion

The analysis concludes that house prices are primarily driven by living area, construction quality, and interior features rather than lot size or number of bedrooms. These findings are essential for building accurate predictive models and improving real estate valuation strategies.
