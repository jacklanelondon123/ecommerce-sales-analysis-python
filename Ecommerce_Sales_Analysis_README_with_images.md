# 🧾 E-Commerce Sales Analysis & Forecasting Using Python

## 🧩 Project Overview
This project explores real-world e-commerce transactions from the **UCI Online Retail II dataset (2009–2011)**.  
The goal was to clean, analyze, and visualize sales performance — identifying key products, customer trends, and forecasting next-month revenue.

---

## 🧰 Tools & Libraries
| Category | Tools Used |
|-----------|-------------|
| Environment | Jupyter Notebook (Anaconda) |
| Data Processing | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Forecasting | scikit-learn (LinearRegression) |

---

## 🧹 Data Cleaning Steps
1. Removed cancelled invoices (IDs starting with “C”).  
2. Dropped rows with missing `CustomerID`.  
3. Filtered only positive `Quantity` and `Price` values.  
4. Created a new `Sales` metric (`Quantity × Price`).  
5. Renamed columns for consistency.  

✅ Final dataset: **407,664 valid transactions**

### 📊 Initial Data Overview
![Initial Data Overview](images/Screenshot%202025-10-14%20000401.png)

### 📊 After Cleaning
![Cleaned Data Summary](images/Screenshot%202025-10-14%20000620.png)

---

## 📊 Exploratory Data Analysis (EDA)

### 🌍 Top 10 Countries by Sales
![Top Countries by Sales](images/Screenshot%202025-10-14%20000912.png)

🧠 *Insight:* Sales are highly concentrated in the UK (≈90%), suggesting strong domestic performance but limited export reach.

---

### 🛍️ Top 10 Products by Sales
![Top Products by Sales](images/Screenshot%202025-10-14%20000931.png)

🧠 *Insight:* Best-selling products are low-cost, decorative giftware — ideal for bundle promotions and cross-selling.

---

### 📈 Monthly Sales Trend
The sales trend shows steady growth throughout 2010 with a sharp spike in **November–December**, confirming **holiday-driven demand**.

![Monthly Sales Trend](images/Screenshot%202025-10-14%20001035.png)

🧠 *Insight:* Seasonal planning before Q4 is critical to capture the biggest revenue window.

---

## 🔮 Forecasting: Linear Regression Trend
Using a simple time-index regression model:

**Predicted next-month sales:** ≈ **£808,000**

![Forecast Trend Line](images/Screenshot%202025-10-14%20001059.png)

🧠 *Insight:* Sales are expected to rise slightly next month, continuing the positive growth trend.

---

## 🧾 Printed Summary Output
![Summary Printout](images/Screenshot%202025-10-14%20001225.png)

---

## 💡 Key Business Recommendations
1. **Scale UK inventory** ahead of Q4 demand peaks.  
2. **Expand into top European markets** (EIRE, Netherlands, Germany).  
3. **Promote high-volume products** via online campaigns and bundles.  
4. **Use predictive models** to plan logistics and marketing around seasonal spikes.  

---

## 🧠 Project Impact
This project demonstrates end-to-end data analysis capabilities:
- Data cleaning and transformation with **pandas**
- Business insight visualization with **matplotlib**
- Simple predictive modelling with **scikit-learn**
- Clear storytelling and recommendations for decision-making  

---

## 📦 Files & Structure
```
📁 ecommerce_python_project
 ┣ 📄 Ecommerce_Sales_Analysis.ipynb
 ┣ 📄 Ecommerce_Sales_Analysis_README.md
 ┣ 📁 images
 ┃   ┣ Screenshot 2025-10-14 000401.png
 ┃   ┣ Screenshot 2025-10-14 000620.png
 ┃   ┣ Screenshot 2025-10-14 000912.png
 ┃   ┣ Screenshot 2025-10-14 000931.png
 ┃   ┣ Screenshot 2025-10-14 001035.png
 ┃   ┣ Screenshot 2025-10-14 001059.png
 ┃   ┗ Screenshot 2025-10-14 001225.png
 ┗ 📁 data
     ┗ online_retail_II.xlsx
```

---

## 🏁 Next Steps
1. Re-create visuals in **Tableau or Power BI** for interactive dashboards.  
2. Automate SQL + Python data pipelines for repeatable reporting.  
3. Extend forecasting with **ARIMA / Prophet** for seasonality.  

---

## ✨ Final Summary
> This project highlights a full analytical workflow — from data cleaning and EDA to forecasting and actionable insight generation.  
> It demonstrates both technical skill in Python and business understanding of retail sales patterns.
