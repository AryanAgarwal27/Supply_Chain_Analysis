# Supply Chain Analysis Project

This project explores and analyzes the **DataCo Supply Chain Dataset** with the goal of identifying actionable insights across customer segmentation, fraud detection, and sales forecasting.

## 📊 Dashboard 
### 🔹 Dashboard 1 – Customer Segmentation & RFM Insights
![Dashboard 1](https://github.com/AryanAgarwal27/Supply_Chain_Analysis/blob/main/Tableau/Dashboard1.png)

### 🔹 Dashboard 2 – Sales, Margins, and Delivery Analysis
![Dashboard 2](https://github.com/AryanAgarwal27/Supply_Chain_Analysis/blob/main/Tableau/Dashboard2.png)

👉 **[Click here to view the live Tableau dashboard](https://public.tableau.com/app/profile/aryan.agarwal1594/viz/Supply_Chain_Analysis_17501755107720/DashBoard1)**


## 📁 Dataset

- **Source**: DataCo Supply Chain Dataset
- **Size**: 180,519 records
- **Features**: Includes customer info, shipping details, sales metrics, returns, and more.

## 🔍 Objectives

- Segment customers based on transaction behavior
- Detect fraudulent transactions
- Forecast future sales trends for inventory optimization

## 🧠 Techniques Used

### Customer Segmentation

- **RFM Analysis**: Recency, Frequency, Monetary scoring
- **Clustering**: K-Means applied to RFM scores
- **Dashboard**: Interactive customer profile exploration in Tableau

### Fraud Detection

- **Data Balancing**: SMOTE used to address class imbalance
- **Modeling**:
  - Random Forest
  - XGBoost
  - CatBoost
- **Metrics**: Precision, Recall, F1-Score for fraud identification

### Sales Forecasting

- **Time Series Models**:
  - ARIMA for univariate forecasts
  - LSTM for sequential modeling of sales data
- **Evaluation**: RMSE and MAE used to validate prediction accuracy

## 📈 Tools & Libraries

- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, catboost, imbalanced-learn
- **Machine Learning**: SMOTE, Random Forest, XGBoost, CatBoost
- **Deep Learning**: LSTM (Keras)
- **Time Series**: statsmodels (ARIMA)
- **Dashboarding**: Tableau (linked above)

## 🔍 Key Insights

- High RFM customers showed a significantly lower return rate and higher average profit.
- Fraudulent orders showed distinct patterns in shipment modes and customer types.
- LSTM outperformed traditional time series models for high-volume sales prediction.

## 📌 Applications

- **Marketing**: Focus on high-value clusters identified via RFM segmentation.
- **Fraud Prevention**: Deploy predictive models to flag risky transactions.
- **Inventory Planning**: Use forecast models for dynamic stock management.

---

## 👤 Author

**Aryan Alpesh Agarwal**  
MSIS Graduate Student, California State University, Fullerton  
📧 [aryanagarwal1227@gmail.com](mailto:aryanagarwal1227@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/aryanagarwal27/) | [GitHub](https://github.com/AryanAgarwal27)

> _"Transforming raw data into actionable business intelligence."_
