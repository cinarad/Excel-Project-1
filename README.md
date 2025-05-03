# 📊 Retail Sales Performance Dashboard (Excel)

This project showcases a **Retail Sales Performance Dashboard** built entirely in **Microsoft Excel**, using a dataset of over 200 retail transactions for a fictional company from 1 year (2024). The goal of this dashboard is to provide **clear, interactive insights** into key sales metrics—including total revenue, regional trends, product performance, and monthly sales patterns.

It is designed to support **data-driven decision-making** for sales managers and stakeholders, demonstrating how Excel’s powerful analytics and visualization tools can be applied to real-world business scenarios.

---

### ✅ Initial Data Preparation

Before dashboard development, the dataset was cleaned and structured for effective analysis:

- **Date Formatting**: Converted the `Date` column to **Short Date format** to ensure consistency.
- **Currency Formatting**: Formatted the `Sales` column to include the appropriate **currency symbol**.
- **Sheet Naming**: Renamed the raw data worksheet to `Retail_Sales_Data` for clarity.

#### 👥 Salesperson Mapping:
To enable more efficient referencing:
- Added a new column: `ID_Salesperson` to the main sales table.  
- Created a **reference table** with unique salesperson names and assigned each a unique ID.

  ![image](https://github.com/user-attachments/assets/72a2e73c-f685-45cd-a776-af79e562aa69)
  
- Used the **`XLOOKUP`** function to match names from the raw data and populate the `ID_Salesperson` column accordingly.

![image](https://github.com/user-attachments/assets/d1b6e9f5-9400-4df5-819c-c3265d00e13d)

---

### 🔧 Tools & Skills Demonstrated

- **Formulas & Functions**: `IF`, `VLOOKUP`, `INDEX-MATCH`, `TEXT`, `SUMIFS`, `AVERAGEIFS`, `DATE`, and more.
- **PivotTables & PivotCharts** for summarizing data visually and interactively.
- **Slicers** for dynamic filtering by region, category, and salesperson.
- **Conditional Formatting** to highlight key performance indicators and trends.
- **Data Cleaning & Transformation** using Excel’s built-in functions.
- **Professional Dashboard Design** with a focus on clarity, usability, and layout.

---
### Insert Pivot Tables
•	It was inserted pivot tables in a new worksheet – Pivot_Tables:
1.	Sales by Region: Display total sales aggregated by region.
   
 ![image](https://github.com/user-attachments/assets/933dad92-ca30-4b49-97ee-76f15b0c2d85)


3.	Monthly Sales Trend: Shows total sales per month to identify trends over time, highlighting seasonal patterns or sales peaks.
   
 ![image](https://github.com/user-attachments/assets/7ff122a5-d99d-45e8-9567-30d796862237)


5.	Sales by Product and Category: Breaks down sales data by individual product and its category. Understanding product performance within categories.
   
 ![image](https://github.com/user-attachments/assets/342f05a4-0c9c-4ac6-a8f5-868d6911e86a)

---
### Create Pivot Charts and Slicers

Pivot Charts were created from the above PivotTables to provide visual insights. Slicers were added for interactive filtering by: Region, Month, Category and ID_Salesperson.
These tools enhance the dashboard’s usability, allowing users to explore the data dynamically.

 ![image](https://github.com/user-attachments/assets/74efcb03-0eef-4bb5-a8c7-2d349ad15d74)






