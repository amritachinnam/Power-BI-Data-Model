# Power-BI-Data-Model


# 📊 **Seven Sages Brewing Company - Power BI Data Model**  

## 🏢 **Project Overview**  

This project focuses on designing a **Power BI data model** for **Seven Sages Brewing Company**, utilizing multiple datasets to build an optimized **star schema**, create **DAX-driven insights**, and develop an **interactive dashboard** for business analytics.

## 🎯 **Objectives**  

✅ **Transform & Clean Data** from multiple sources (Excel, TXT, PDF, CSV)  

✅ **Develop a Star Schema** to ensure efficient data relationships  

✅ **Use DAX Functions** to compute key performance metrics  

✅ **Enable Multi-Currency Reporting** for USD-CAD conversion  

✅ **Build an Interactive Dashboard** for executive-level insights  

✅ **Create a Custom Date Table** from scratch for time intelligence  


## 🗂️ **Datasets & Data Transformation Techniques**  

This project worked with **multiple files** for **data modeling and transformation**:

### **1️⃣ CFO Metrics Tracker (Excel)**  

- Includes financial performance metrics  
- Used for **cost analysis, profitability ranking, and BeerAdvocate scores**  

### **2️⃣ Customer List (TXT)**  

- Contains **customer types** (bars, distributors, tasting rooms)  
- Cleaned inconsistencies in **state/province names**  
- Used **unique identifiers (PKCustomerID)** for **joins**  

### **3️⃣ SSBC Product Offerings (PDF)**  

- Extracted **beer product details** (ABV %, IBU, descriptions)
- 
- Merged **description columns** to handle **text-based product details**
- 
- Used **Fill Down** method to address **missing product names**
- 
- Created **custom columns** to categorize products  

### **4️⃣ USD-CAD Exchange Rates (CSV)**  

- Used for **real-time currency conversion**
- 
- Enabled **dynamic exchange rate adjustments** in reports  

### **5️⃣ Custom Date Table (Created from Scratch in Power BI)**  

- Built using **Power Query**, dynamically updates based on the **fact table's start and end dates**  
- Includes:  
  - **Calendar month name**  
  - **Calendar year** 
  - **Month**
  -  **Dates** 
  - **Fiscal year**  
  - **Fiscal quarter name (e.g., Q1FY 2021)**  

📌 **Note:** Seven Sages’ **Fiscal Year** begins on **October 1st** and runs until **September 30th**. A transaction on **September 20th, 2020**, falls in **FY 2020**, while a transaction on **October 20th, 2020**, lands in **FY 2021**.


## 📌 **Power BI Data Model (Star Schema)**  

This **star schema** enhances **query speed, filtering, and DAX calculations**.

| **Table Type** | **Table Name** | **Purpose** |
|---------------|--------------|------------|
| **Fact Table** | `Full 2021 Sales` | Stores all sales transactions |
| **Dimension Table** | `Customer List` | Customer details (bars, distributors, tasting rooms) |
| **Dimension Table** | `Product_CP` | Product details (name, type, ABV, IBU) |
| **Dimension Table** | `DateTable` | **Custom-built date table for time intelligence** |
| **Dimension Table** | `CFO Metrics` | Financial metrics (cost rank, sales rank) |
| **Dimension Table** | `USD-CAD Exchange Rates` | Multi-currency conversion for sales reports |

![image](https://github.com/user-attachments/assets/a3227430-b032-42dc-bb68-04d9cea10753)


## 🚀 **Key Insights from the Power BI Dashboard**  

The final **summary insights** were computed using **DAX formulas** and **Power BI visualizations**:

### 📌 **Customer Type Sales & Gross Profit Margin Analysis**  
- **Highest Sales Customer Type**: Distributor with **total sales of $94,436**  
- **Highest Gross Profit Margin Customer Type**: SSBC Tasting Room with **66.94% margin**  

 ![image](https://github.com/user-attachments/assets/7c64338a-6f84-4013-bc63-c07f72288354)


### 📌 **Top-Selling & Most Profitable Products**  
- **Best-selling beer**: **Bamboo Grove Maibock** with **29.41% of total sales**  
- **Most profitable beer**: **Bamboo Grove Maibock** with **31.27% gross profit**  
- **Lowest profit beer**: **Scholar’s Saison** with **0.32% gross profit**  

![image](https://github.com/user-attachments/assets/dbe3e756-6ee4-4a62-94c5-f70e9b0be964)


---

## 🏆 **Key Learnings & Takeaways**  

✔️ **Power BI can fully handle complex data transformation** without external tools  
✔️ **Working with PDFs requires strategic cleaning techniques** (merging, fill-down, custom columns)  
✔️ **DAX functions are powerful for business intelligence calculations**  
✔️ **A well-structured star schema leads to faster queries and efficient reporting**  
✔️ **Creating a custom Date Table allows for flexible time-based analysis**  


### 📌 **Connect with Me**  
📧 Email: amritachinnam2@gmail.com
📎 LinkedIn: [[Your LinkedIn Profile]  ](https://www.linkedin.com/in/amrita-chinnam-866545190/)


