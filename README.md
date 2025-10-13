
# 🛒 Ecommerce Sales Analysis (Python Project)

This project uses Python and Jupyter Notebook to perform data cleaning, exploration, and visualization on the **Online Retail II dataset**.  
It aims to identify top countries, best-selling products, and forecast future sales trends.

---

## 📦 1. Data Loading and Overview
We start by loading the dataset and displaying a summary of columns and data types.

![Data Overview](Screenshot%202025-10-14%20000401.png)

---

## 🧹 2. Data Cleaning and Feature Engineering
After removing missing and invalid records, we added a **Sales** column (`Quantity × Price`).

![Data Cleaning Summary](Screenshot%202025-10-14%20000620.png)

---

## 🌍 3. Top 10 Countries by Sales
We calculated total sales by country to identify the most profitable markets.

![Top Countries](Screenshot%202025-10-14%20000912.png)

---

## 🛍️ 4. Top 10 Products by Sales
We grouped sales by product description to identify the best sellers.

![Top Products](Screenshot%202025-10-14%20000931.png)

---

## 📈 5. Monthly Sales Trend
We aggregated sales data by month to observe performance over time.

![Monthly Sales Trend](Screenshot%202025-10-14%20001035.png)

---

## 🔮 6. Sales Forecast (Linear Trend)
A simple linear regression model was used to forecast future monthly sales.

![Linear Trend Forecast](Screenshot%202025-10-14%20001059.png)

---

## 🧠 7. Insights
- The **United Kingdom** dominates sales, contributing the majority of total revenue.  
- **Gift and home decor products** lead the best-seller list.  
- Sales show **seasonal peaks** toward the end of the year.  
- The linear trend indicates **steady overall growth** with room for forecasting improvements.

---

## 💾 Files in this Project
| File | Description |
|------|--------------|
| `Ecommerce_Sales_Analysis.ipynb` | Main Jupyter Notebook with all Python analysis |
| `README.md` | Project overview (this file) |
| `Online_Retail_II.xlsx` | Raw dataset used in the analysis |

---

## 🏁 Conclusion
This project demonstrates practical **data analysis and visualization in Python**, combining `pandas`, `matplotlib`, and `scikit-learn` for real-world ecommerce insights.

