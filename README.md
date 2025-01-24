# Online Retail-Insight-Dashboard


This repository contains the Power BI project that analyzes retail data to generate actionable insights. The analysis focuses on answering key business questions of the retail company. The dataset has been thoroughly cleaned, and visuals have been created to address their specific concerns.

![Image](https://github.com/user-attachments/assets/7d1a211f-8174-4ce0-aa68-6699b111f399)

---

## 📊 **Project Overview**

This analysis uses Power BI to explore the retail dataset and derive insights related to revenue, customer behavior, and product demand. The dataset includes transaction records such as quantity, unit price, customer information, and country.

The analysis addresses the following key questions:

1. **Monthly Revenue Trends for 2011** (CEO)
2. **Top 10 Countries by Revenue and Quantity (Excluding UK)** (CMO)
3. **Top 10 Customers by Revenue** (CMO)
4. **Product Demand by Country (Excluding UK)** (CEO)

---

## ⚙️ **Steps Performed**

### **1. Data Cleaning**
The dataset contained some invalid entries, such as:
- Negative quantities (indicating returns).
- Unit prices below $0 (input errors).

Steps taken:
- Filtered out transactions with quantities less than 1.
- Removed records where unit price was below $0.
- Ensured the dataset was ready for analysis using Power Query in Power BI.

---

## 🔍 **Insights**

### **1. Monthly Revenue Trends for 2011**
- **Visual**: Line Chart
- **Insight**: Revenue peaked in **November 2011**, likely due to holiday shopping trends.
- **Action**: Use this trend to forecast revenue for future years and optimize inventory and promotions around high-revenue months.

### **2. Top 10 Countries by Revenue and Quantity (Excluding UK)**
- **Visual**: Bar Chart
- **Insight**:
  - Countries like **Netherlands**, **Germany**, and **France** generated the highest revenue.
  - Some countries showed high revenue but lower quantities, indicating opportunities to optimize pricing strategies.
- **Action**: Prioritize these countries for marketing and expansion initiatives.

### **3. Top 10 Customers by Revenue**
- **Visual**: Bar Chart
- **Insight**:
  - Top customers are ranked by revenue, with the highest revenue generator contributing significantly more than others.
  - These customers represent a vital segment for loyalty-building strategies.
- **Action**: Develop personalized offers or loyalty programs to retain high-value customers.

### **4. Product Demand by Country (Excluding UK)**
- **Visual**: Map Visualization
- **Insight**:
  - Countries like **Netherlands**, **Germany**, and **EIRE** showed the greatest demand for products.
  - These regions are ideal for market expansion.
- **Action**: Focus expansion efforts on these high-demand areas to capture more market share.

---

## 🛠️ **Tools Used**

- **Power BI**: For data visualization and analysis.
- **Power Query**: For data cleaning and transformation.

---

## 📂 **Repository Contents**

- `Online Retail Dataset.xlsx`: The original dataset used for analysis.
- `Retail_Analysis.pbix`: The Power BI project file containing all visuals and data transformations.
- `Insights_Screenshots/`: Screenshots of the visuals for quick reference.

---


