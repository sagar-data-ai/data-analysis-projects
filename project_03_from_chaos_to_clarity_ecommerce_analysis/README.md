
# 🛒 **Project – From Chaos to Clarity: E‑Commerce Data Analysis**

### 📊 A Comprehensive Data Cleaning and Exploratory Analysis Project

---

## 🚀 **Overview**

This project demonstrates how data quality transforms business decision‑making in an e‑commerce setting.  
Using the **Brazilian E‑Commerce Public Dataset (by Olist)**, this analysis takes the raw messy data and shows how cleaning and structure turn chaos into clarity.

**Phases:**
1. Data Assessment and Diagnosis  
2. Data Cleaning and Feature Engineering  
3. EDA on Uncleaned vs Cleaned Data  
4. SQL Insights Validation  
5. Power BI Dashboard Summary  


---

## 🧩 **Dataset Details**

| Attribute | Description |
|:--|:--|
| **Source** | Brazilian E‑Commerce Public Dataset by Olist (Kaggle) |
| **Time Range** | 2016 – 2018 |
| **Records** | ~115,610 (uncleaned) → 96,516 (cleaned) |
| **Files Merged** | Customers, Orders, Sellers, Products, Payments, Reviews, Geolocation, Categories |
| **Tech Stack** | Python (pandas, numpy, seaborn, matplotlib), MySQL, Power BI |

---

## 🧠 **Objective**

> To analyze how unclean data creates false business impressions and how cleaning and structure reveal the real market picture.

---

## ⚙️ **Process Workflow**


**Workflow:**  
1️⃣ Data Assessment → 2️⃣ EDA on Uncleaned Data → 3️⃣ Data Cleaning → 4️⃣ EDA on Cleaned Data → 5️⃣ SQL Insights → 6️⃣ Dashboard & Report  

**Key Cleaning Steps**
- Removed duplicates (~10%)
- Managed null values & bounded outliers  
- Engineered new features (`delivery_time`, `product_density`, `items_in_order`)  
- Standardized category & region labels  
- Grouped minor states as *“Other”* for balance  

---

## 📈 **EDA Highlights**

### 🔹 Before Cleaning (Uncleaned Data)

- Random, chaotic relationships (e.g., price vs freight).
- Unrealistic shipping costs & missing delivery dates.  
- Highly skewed ratings (1★ and 5★ only).  
- Multi‑payment duplicates inflating revenue.

### 🔹 After Cleaning (Cleaned Data)

| Metric | Before | After | Improvement |
|:--|:--|:--|:--|
| Freight Variance | 150 | 15 | ‑90 % Noise Removed |
| Duplicate Entries | ~10 % | 0 % | 100 % Integrity |
| Delivery Coverage | 97.5 % | 100 % | Complete Dataset |
| Insight Accuracy | ≈ 70 % | ≈ 94 % | +24 % Improvement 📈 |

---

## 🧮 **SQL Insights**

15 SQL queries were executed to support analytical observations.

**Key Analytical Queries**
| Focus | Example Result |
|:--|:--|
| Average Delivery Time by State | ~11 days (SP fastest) |
| Top 5 Categories by Revenue | Home > Electronics > Health |
| Delivery Delay vs Rating | Delay > 30 days → ‑1.5★ rating |
| Payment Type vs EMI | High value orders → 2‑4 installments |
| Seller State vs Rating | Average rating ≈ 4 ⭐ nationwide |


---

## 💼 **Business Insights**

### 📦 Operations
- Established national average delivery = 11 days.  
- Multi‑item orders take +3 days more to ship.  

### 💳 Finance
- Cleaned revenue revealed ~10 % overstatement in unclean data.  
- High‑value orders (>₹ 2000) mainly use installments.  

### 💬 Customer Experience
- Delivery ≤ 10 days → avg rating ≥ 4.2.  
- Delays > 25 days → ratings ≈ 3 ★.  

### 🌍 Regional Performance
- SP & MG – fastest deliveries.  
- PR, RS, SC – slower (~3‑4 days delay).  

---

## 💡 **Business Impact Summary**

| Domain | Impact |
|:--|:--|
| **Operational Efficiency** | Delivery SLA established, delay ↓ 20 % |
| **Financial Accuracy** | Eliminated duplicate revenues |
| **Customer Retention** | Evidence‑based relationship: delay ↓ rating ↑ |
| **Market Growth** | Balanced regional data boosted expansion planning |

---

## 🧭 **Recommendations**

- Maintain average delivery ≤ 10 days to preserve ratings ≥ 4.2⭐  
- Promote EMI options for high‑value orders (↑ AOV 8‑10 %).  
- Add distribution centers in southern regions (‑20 % delay).  
- Implement monthly data audits to sustain data integrity.

---

## 🧰 **Tech Stack**

| Category | Tools |
|:--|:--|
| Data Cleaning & EDA | Python (pandas, numpy, seaborn, matplotlib) |
| Database Validation | MySQL Workbench |
| Visualization & Reporting | Power BI |


---

## 🏁 **Conclusion**

> **Clean data reveals the truth behind business performance.**  

When information is organized, the company can see its real strengths and weaknesses — from customer satisfaction to logistics efficiency and revenue accuracy.  
This project marks the transition from *assumption‑based* analysis to *evidence‑based* strategy.

> *“From chaotic records to data‑driven growth — transforming information into intelligence.”*

---

## 📂 Project Folder Structure

- **data** – Dataset files (actual data- Ecommerce, cleaned data - final_data)  
- **notebooks** – Python notebooks for data cleaning, data assessing, and EDA  
- **sql** – SQL queries used for analysis and insights  
- **conclusion** – Final outputs such as reports, PPTs, and dashboards  
- **README** – Project overview, objectives, and key findings

    

---

## ✨ Author

**Sagar Kumar**

**Social Links** - [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/sagar-datascience) [![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/sagar-data-ai) 
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://portfolio-sagar-v2.vercel.app)

