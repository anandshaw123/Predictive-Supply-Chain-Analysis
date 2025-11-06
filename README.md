# Predictive Supply Chain Analysis

# 🚚 Predictive Supply Chain Analysis – Data-Driven Optimization & Prediction

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-RandomForest-orange)
![EDA](https://img.shields.io/badge/EDA-Plotly%20%7C%20Seaborn-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 🧭 Project Overview
This project focuses on analyzing and predicting supply chain performance using the **DataCo Supply Chain Dataset**.  
It covers **exploratory data analysis (EDA)**, **geographical and customer insights**, and **predictive modeling** to detect **fraudulent orders**, **delivery risks**, and **sales forecasting**.

By leveraging **data visualization** and **machine learning**, this project helps businesses identify weak areas in logistics and optimize decision-making for better operational efficiency.

---

## 🎯 Objectives
- Understand key factors affecting **delivery performance, profit, and customer behavior**.  
- Predict whether an order is **fraudulent or not**.  
- Forecast **late deliveries** based on historical data.  
- Identify **top customers, categories, and regions** driving revenue.  
- Derive **insights** to optimize supply chain efficiency and minimize risks.

---

## ❓ Business Questions
1. Which regions and countries experience the most **late deliveries**?  
2. Who are the **top customers** by order quantity and profit?  
3. What are the **most profitable product categories** and **best-performing regions**?  
4. Can we **predict fraudulent orders** with high accuracy?  
5. What are the **key delivery and logistic variables** affecting customer satisfaction?  
6. How do **sales trends** vary by year, quarter, and month?

---

## 🧰 Tools & Libraries Used
| Purpose | Tools / Libraries |
|----------|------------------|
| Data Manipulation | `pandas`, `numpy` |
| Data Visualization | `matplotlib`, `seaborn`, `plotly.express`, `plotly.graph_objects` |
| Machine Learning | `scikit-learn`, `xgboost` |
| Preprocessing | `LabelEncoder`, `StandardScaler` |
| Model Evaluation | `accuracy_score`, `roc_auc_score`, `classification_report`, `confusion_matrix` |

---

## 📊 Exploratory Data Analysis (EDA)
Key findings from visualization and exploration:
- **Central America** and **Western Europe** had the **highest number of late deliveries**.  
- The **Consumer Segment** made up the largest share of total orders.  
- **Top-performing countries**: Dominican Republic, USA, and Honduras.  
- **Best product categories**: Sporting Goods, Fan Shop.  
- **High-profit customers** significantly contributed to overall revenue.

---

## 🤖 Machine Learning Models

### 1. 🕵️ Fraud Detection Model
- **Algorithm:** Random Forest Classifier  
- **Accuracy:** 99.62%  
- **ROC-AUC:** 0.95  
- **F1 Score:** 0.96  
- **Insight:** Order `Type`, `Delivery Status`, and `Region` were key fraud indicators.

### 2. ⏰ Late Delivery Prediction
- **Algorithm:** Random Forest (Entropy, log2 features)  
- **Accuracy:** 94.7%  
- **ROC-AUC:** 0.94  
- **F1 Score:** 0.95  
- **Insight:** Delivery delays were heavily influenced by **shipping mode** and **region**.

### 3. 💰 Sales Forecasting
- Forecasted sales performance across countries, products, and categories.
- Seasonal trends showed peak activity in **Q4**, indicating **holiday-driven demand**.

---



## 📈 Model Performance Summary

| Model             | Accuracy |
| ----------------- | -------- |
| Linear Regression | **0.78** |
| Ridge Regression  | **0.78** |
| Lasso Regression  | **0.78** |
| Random Forest     | **0.99** |
| XGBoost           | **0.99** |
| Decision Tree     | **0.93** |














---



## 💡 Key Insights
| Area | Insight |
|------|----------|
| 📦 Delivery | Central America and Western Europe suffer from high late-delivery rates. |
| 👥 Customers | A small group of customers drives a large portion of profit and sales. |
| 🛍️ Products | “Smart Watch” and “Field & Stream Gun Safe” are top-selling, high-profit products. |
| 🌍 Geography | Dominican Republic and USA are leading markets by profit. |
| ⚙️ Operations | “Standard Class” shipping dominates but contributes to more delays. |

---

## 🧩 Recommendations
1. **Improve logistics performance** in high-delay regions through better route planning.  
2. **Implement fraud detection** automation using the Random Forest model.  
3. **Reward high-value customers** with loyalty incentives.  
4. **Optimize shipping modes** to balance cost and timely delivery.  
5. **Use quarterly insights** for targeted inventory and marketing strategies.  
6. **Integrate predictive models** into ERP systems for proactive risk alerts.





