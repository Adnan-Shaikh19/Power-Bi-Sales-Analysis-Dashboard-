# 📊 E-Commerce Store Sales Dashboard (Power BI)

## 📌 Project Overview
This project presents an interactive **Power BI Sales Dashboard** created to analyze the revenue, profitability, and operational performance of an e-commerce platform. The project processes transactional order details and customer location data to track key performance metrics, regional sales distributions, category profitability, and customer payment preferences.

---

## 📊 Key Performance Indicators (KPIs)
- **Total Revenue (Amount):** ₹438K
- **Total Profit:** ₹37K
- **Total Quantity Sold:** 5,615 Units
- **Average Order Value (AOV):** ₹121K

---

## 🛠️ Data Architecture & Modeling
- **Data Source:** `Orders.csv` (Order Date, Customer Name, State, City) & `Details.csv` (Amount, Profit, Quantity, Category, Sub-Category, Payment Mode).
- **Data Model:** Established a Star Schema with a 1-to-Many relationship between `Orders` (1) and `Details` (*)[cite: 14].
- **DAX Calculations:** Built custom measures for total sales, profitability, unit counts, and Average Order Value (AOV).

---

## 📈 Visualizations & Key Business Insights
1. **Regional Sales Distribution:** **Maharashtra** (₹0.10M) and **Madhya Pradesh** (₹0.09M) lead overall sales revenue.
2. **Category Volume:** **Clothing** dominates total units sold at **62.62%**, followed by Electronics (**20.55%**) and Furniture (**16.83%**).
3. **Payment Preferences:** **COD (Cash on Delivery)** is the most preferred payment method at **43.74%**, followed by UPI (**20.61%**) and Debit Card (**13.20%**).
4. **Profitability Trends:** Peak monthly profit was achieved in **December (₹10.3K)** and **January (₹9.7K)**, while **May (-₹3.7K)** experienced the highest profit dip.
5. **Top Sub-Categories by Profit:** **Printers (₹8.6K)** and **Bookcases (₹6.5K)** generated the highest sub-category profit.

---

## 🎯 Interactive Controls
- **Quarterly Slicers:** Quick filtering across Qtr 1, Qtr 2, Qtr 3, and Qtr 4[cite: 13].
- **State Filter:** Dropdown filter enabling state-by-state granular analysis[cite: 13].
