
# 🛒 Sales & Inventory Data Analysis with Power BI

## 📊 Overview

This Power BI project provides a detailed sales and inventory analysis based on transactional data. The dashboard delivers insights into customer purchases, product performance, pricing, and sales patterns, enabling data-driven decisions for marketing, inventory management, and pricing strategies.

---
## 📷 Dashboard Preview

<img width="698" alt="Sales and Inventory Analysis" src="https://github.com/user-attachments/assets/72f05a8b-d0d4-43ee-a3ef-31228cd34a5d" />

---

## 🎯 Objectives

This report addresses the following business questions:

1. **Most Quantity Purchased by Customer**  
   - Identify which customers purchased the highest quantities overall.

2. **Quantity, Total Amount, and Unit Price of Products by Name and Category**  
   - Analyze key sales metrics grouped by product name and category.

3. **Unit Price by Product Name and Category**  
   - Understand product pricing trends across categories.

4. **Amount by Gender and Birth Year**  
   - View total purchase amounts broken down by customer demographics.

5. **Top 3 Least Sold Products**  
   - Identify products with the lowest total sales volume.

6. **Top 3 Most Sold Products**  
   - Highlight the best-selling products by quantity.

7. **Top 3 Most Expensive Products**  
   - List the products with the highest unit prices.

---

## 💳 KPI Cards

These key metrics are shown using **cards** for at-a-glance visibility:

- **Total Sales**
- **Total Discount Given**
- **Total Quantity Sold**

---

## 📂 Dataset

- **File Used:** <a href="https://github.com/edinakanlic/Sales-Inventory-Analysis-Power-BI/blob/main/Fruit%20Sales%20Data%20-%20Inventory%20and%20Sales.xlsx">Sales and Inventory dataset</a>
- **Key Columns:**
   `ProductName`, `Product Category`, `Quantity`, `UnitPrice`, `Discount`, `TotalAmount`, `Gender`, `Birthdate`

---

## 🔍 Data Analysis Process

### 1. Data Loading & Cleansing
- Loaded dataset into Power BI from xlsx format.
- Removed nulls from critical fields like `ProductName`, `Quantity`, `TotalAmount`.
- Ensured proper data types: dates, decimals, integers.
- Merged queries and replaced values

### 2. Visualizations
- **Bar Chart** for *Most Quantity Purchased by Customer*  
  (e.g., Amina Loo: 100%, Coralie Brent: ~90%)

- **Donut Charts** for:  
  - *Top 3 Most Sold Products*: Asparagus, Carrot, Rhubarb  
  - *Top 3 Least Sold Products*: Cranberry, Peach, Lemon  
  - *Top 3 Most Expensive Products*: Asparagus (651.05), Rhubarb (418.51), Strawberry (255.64)

- **Stacked Column Area Chart** for *Amount by Gender and Birth Year*  
  - Sales trends from 1940 to 1990 split by gender

- **Card Visuals (KPIs)**  
  - Total Sales: **1.15K**  
  - Total Quantity Sold: **952**  
  - Total Discount Given: **266.60**

- **Scatter Chart** for *Quantity, Total Amount & Unit Pricce by Name and Category*  
  - Represents multidimensional product performance

- **Stacked column Chart** for *Unit Price by Product and Category*  
  - Highest: Asparagus (194), Rhubarb (119), Strawberry (95)

---

## 📈 Key Insights

- Certain customers consistently purchase in bulk, revealing potential for loyalty campaigns.
- The majority of high-revenue products fall within [Vegetables].
- Gender and age demographics influence buying power and sales volume.
- High-value products don’t always correlate with high sales quantity.
- A few underperforming products may need reevaluation or promotion.

---

## 🛠️ Tools Used

- Power BI Desktop  
- Power Query for data preparation  
- Excel file as the primary data source

---

## ▶️ How to Use

1. Clone this repository or download the files.  
2. Open the `.pbix` file with Power BI Desktop.  
3. Load or replace the `Fruit Sales Data - Inventory and Sales.xlsx` file.  

---

