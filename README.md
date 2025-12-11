# 🚚 Logistics Revenue & Cost Analytics Dashboard | Power BI

**A full end-to-end Business Intelligence project analyzing the financial and operational performance of a logistics fleet using Power BI.**  
This dashboard provides insights into revenue, costs, gross margin, truck performance, operational KPIs, and year-over-year changes to support data-driven decision-making.

---

## 📊 Project Overview

This Power BI report is built using logistics datasets from **Kaggle** and includes **two main dashboards**:

### 1️⃣ Revenue Dashboard
- Total Revenue  
- Gross Margin & Gross Margin %  
- Number of Orders  
- Goods Value  
- Revenue by City & State  
- Revenue by Year & Quarter  
- Revenue by Truck Type & Trailer Type  
- YOY & Year-over-Year Variance  

### 2️⃣ Cost Dashboard
- Total Cost  
- Cost per Truck & Cost per Order  
- Fuel, Maintenance & Fixed Cost Analysis  
- Cost by Trailer & Truck Type  
- Cost by Year & Quarter  
- YOY & Year-over-Year Variance  

---

## 🧠 Key Insights

### ⭐ Overall Financial Performance
- **Total Revenue:** $484M  
- **Total Cost:** $3.77M  
- **Gross Margin:** Positive across most truck/trailer types  

### 📉 Year-over-Year (2019 vs 2018)
- Revenue decreased by **$22,506,741 (-8.9%)**  
- Gross Margin decreased by **$21,568,186 (-8.6%)**  
- Total Cost decreased by **$938,555 (-39.9%)**  

> **Interpretation:**  
Revenue & margin drop indicates lower operational activity.  
Cost reduction (-39.9%) suggests fewer routes, reduced fuel usage, fewer maintenance events, and overall downsizing. Despite cost savings, net financial performance weakens due to revenue and margin decline.

### 📈 Revenue Insights
- Highest revenue states: **WV, OK, SC**  
- Top cities: **Bloom, Sandy Lane, Mineola**  
- Trailer truck type revenue: **$92M+**  
- Revenue peaked **Q1–Q2 2019**, then declined  
- Strong correlation between **goods value** and **revenue**  

### 💰 Cost Insights
- Average cost per truck: **$122K**  
- Reefer Trailers highest fuel + maintenance cost: **$1.79M**  
- Truck Type Trailer highest yearly cost: **$1.9M**  
- Fixed Costs = **69% of total operational expense**  

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- Power Query  
- DAX Measures  
- Data Modeling (Star Schema)  
- Kaggle Datasets  
- Excel & CSV Preparation  

---

## 🧱 Data Model

**Star Schema Structure:**

- **Fact Tables:** Freight, FCost  
- **Dimension Tables:** Date, Drivers, Customers, Vehicles  
- **Relationships:** Truck ID, Customer ID, Driver ID, Date  

---

## 📷 Dashboard Preview

<img width="1295" height="720" alt="image" src="https://github.com/user-attachments/assets/b0f89317-abe0-4b04-98cb-d46b28378a60" />

<img width="1281" height="715" alt="image" src="https://github.com/user-attachments/assets/1f011d4e-5ea5-486c-a6f0-21831e079068" />

---

## ✅ Highlights
- End-to-end analytics workflow  
- Revenue vs. cost insights  
- YOY & QoQ performance comparison  
- Actionable operational KPIs  
