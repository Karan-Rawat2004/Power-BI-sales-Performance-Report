# 📊 Sales Performance Report – Power BI  

## 📌 Overview  
This Power BI project presents an **interactive Sales Performance Dashboard** analyzing revenue, gross profit, and quantity sold across multiple products, accounts, and time periods.  
The report leverages **time intelligence functions** to compare **Year-to-Date (YTD)** performance against **Previous Year-to-Date (PYTD)**, enabling insights into trends and seasonal variations.  

---

## 📂 Dataset Structure  
The data model is built with **one fact table** and **three dimension tables**:  

- **Fact_Sales**  
  - `Product_ID`: Unique product identifier  
  - `Sales_USD`: Total sales amount in USD  
  - `Quantity`: Number of units sold  
  - `Price_USD`: Price per unit in USD  
  - `COGS_USD`: Cost of Goods Sold in USD  
  - `Date_Time`: Transaction date  
  - `Account_ID`: Customer/account reference  

- **Dim_Product**  
  - Product details including name, category, and sub-category  

- **Dim_Account**  
  - Account/customer details, including **Country/Region** for geographical analysis  

- **Dim_Date**  
  - Custom date table created in Power BI for time-based calculations  

---

## 📸 Dashboard Preview  
![Sales Performance Dashboard](https://github.com/Karan-Rawat2004/Power-BI-sales-Performance-Report/blob/main/dashborad.png?raw=true)  

---

## 📈 Insights from the Dashboard  
- **Performance Decline:** PYTD values are higher than YTD in key revenue and profit metrics, indicating reduced performance compared to last year.  
- **Seasonality:** Certain months show significant spikes, suggesting seasonal demand fluctuations.  
- **Profit Drivers:** High-margin products continue to contribute significantly to gross profit despite overall decline.  
- **Top Accounts:** A small group of customers generate the majority of sales, indicating opportunities for targeted engagement.  

---

## 🛠 Tools & Technologies Used  
- **Power BI Desktop** – Data modeling, visualization, and time intelligence  
- **DAX** – For calculated measures such as YTD and PYTD  
- **Excel/CSV** – Source data preparation  
- **Star Schema** – Fact-Dimension modeling for optimal performance  

---

## 📥 How to Use  
1. **Download the `.pbix` file** from this repository.  
2. Open in **Power BI Desktop** (latest version recommended).  
3. Explore visuals with filters, slicers, and drill-down functionality.  

---

## 📜 License  
This project is released under the MIT License – you are free to use and adapt it with attribution.  

---

**💡 Author:** Karan Rawat  
**📅 Created:** 13 August 2025  
**🌐 LinkedIn:** www.linkedin.com/in/karan-rawat-2701kr  



