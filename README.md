# 📊 FMCG Analytics Project

## 🔍 Project Overview  
This project analyzes **FMCG manufacturing performance, production capacity, cost structure, and pricing strategy** using **SQL Server** and **Power BI**.  
It provides end-to-end insights from raw data to interactive dashboards.

---

## 🛠 Tech Stack  
- **SQL Server** – Data modeling & business logic  
- **Power BI** – Visualization & dashboards  
- **GitHub** – Version control & portfolio  



## 🗂 Project Structure  
FMCG-Project/
-│
-├── datasets/ # Raw datasets (CSV / Excel)
-├── sql/ # SQL scripts & views
-├── powerbi/ # Power BI .pbix files
-├── docs/ # Project documentation (Word/PDF)
-└── README.md # Project description




## 🧮 SQL Data Model  
A centralized SQL view was created:

**View Name:**  
`VW_FACT_PRD_MANU_PROD_MASTER_MAIN_NEW_DATA`

### Key Features:
- Pack size parsing (value & unit)  
- Capacity utilization calculation  
- Variance (Actual vs Plan vs Target)  
- Margin & pricing logic  
  - Ex-Factory Price  
  - Wholesale Price  
  - Pre-Tax MRP  
  - MRP  
  - Profit per pack  

---

## 📈 Power BI Reports

### 🏭 Report 1: Manufacturing Unit Performance Analysis  
**Pages:**
- Manufacturing Unit Overview  
- Capacity vs Working Hours  
- Variance Analysis (Actual vs Plan vs Target)  
- Capacity Comparison (Current vs Previous Period)  

**Insights:**
- Identifies under-utilized plants  
- Tracks production efficiency  
- State-wise and unit-wise comparison  

---

### 💰 Report 2: Manufacturing Cost & Production Analysis  
**Pages:**
- Cost Analysis by Pack or Category  
- Production Variance & Performance Bridge  
- Base Cost Variance (Actual vs Plan vs Expected)  
- Pricing Analysis (Ex-factory → MRP)  

**Insights:**
- Cost efficiency by pack size  
- Profit contribution by category  
- Pricing & margin evaluation  

---

## 🔄 End-to-End Flow  
Raw Data → SQL View → Power BI Measures → Dashboards → Business Insights


---

## 📌 Business Value  
- Helps optimize manufacturing utilization  
- Supports cost control decisions  
- Improves pricing and margin strategy  
- Enables management-level performance tracking  

---

## 👤 Author  
**Sainadh Pasupuleti**  
Data Analytics Project (SQL + Power BI)

---

## 🚀 How to Use  
1. Load datasets into SQL Server  
2. Create the SQL view  
3. Connect Power BI to SQL view  
4. Refresh data  
5. Explore dashboards  
