# 📊 Retail Sales Performance Dashboard (Excel)
This self-initiated project was developed as part of my personal learning journey to strengthen my data analysis and visualisation skills using Microsoft Excel. Working with a fictional dataset of over 200 retail transactions from 2024, I designed a dynamic, interactive dashboard to explore key sales metrics such as total revenue, regional trends, monthly sales patterns, and product performance.

The goal of this project was to practice core Excel functionalities—such as data cleaning, formula application, PivotTables, and dashboard design—while simulating a real-world business scenario that supports data-driven decision-making. The final dashboard offers a clear, professional layout with slicers and charts to make insights easily accessible for stakeholders..


### ✅ Step 1: Initial Data Preparation
Before diving into analysis and visualization, the raw dataset underwent structured preparation to ensure accuracy and usability:

Date Formatting: Standardized the Date column using Short Date format.

Currency Formatting: Applied currency formatting to the Sales column for consistency.

Sheet Naming: Renamed the raw data worksheet to Retail_Sales_Data for clarity and easier referencing.

👥 Salesperson Mapping with IDs
To streamline referencing and filtering:

Added a new column: ID_Salesperson to assign a unique identifier to each salesperson.

Created a reference table containing all unique salesperson names with assigned numeric IDs.

Used the XLOOKUP function to link names from the main dataset to their corresponding IDs.

  ![image](https://github.com/user-attachments/assets/72a2e73c-f685-45cd-a776-af79e562aa69)
  

![image](https://github.com/user-attachments/assets/d1b6e9f5-9400-4df5-819c-c3265d00e13d)

---

### 🔧 Step 2: Tools & Skills Demonstrated

- **Formulas & Functions**:  `VLOOKUP`, `INDEX-MATCH`, `TEXT`, `SUM`, `AVERAGE`, `DATE`, and more.
- **PivotTables & PivotCharts** for summarizing data visually and interactively.
- **Slicers** for dynamic filtering by region, category, and salesperson by ID.
- **Data Cleaning & Transformation** using Excel’s built-in functions.
- **Professional Dashboard Design** with a focus on clarity, usability, and layout.

---
### 📊 Step 3: Creating PivotTables
PivotTables were inserted in a separate worksheet named Pivot_Tables to summarize the dataset and support dashboard visualizations:
1.	Sales by Region: Display total sales aggregated by region.
   
 ![image](https://github.com/user-attachments/assets/933dad92-ca30-4b49-97ee-76f15b0c2d85)


3.	Monthly Sales Trend: Shows total sales per month to identify trends over time, highlighting seasonal patterns or sales peaks.
   
 ![image](https://github.com/user-attachments/assets/7ff122a5-d99d-45e8-9567-30d796862237)


5.	Sales by Product and Category: Breaks down sales data by individual product and its category. Understanding product performance within categories.
   
 ![image](https://github.com/user-attachments/assets/342f05a4-0c9c-4ac6-a8f5-868d6911e86a)

---
### 📈 Step 4: Pivot Charts & Slicers
PivotCharts were created based on the tables above to provide clear, visual insights. Slicers were added for dynamic filtering by:

  _>>_ Region

  _>>_ Month

  _>>_ Category

  _>>_ Salesperson ID

This makes the dashboard highly interactive and user-friendly.

 ![image](https://github.com/user-attachments/assets/74efcb03-0eef-4bb5-a8c7-2d349ad15d74)

---
### 🖥️ Final Output: Interactive Dashboard


https://github.com/user-attachments/assets/fec986c6-5c57-4a65-89fe-66165f67996f


The final dashboard allows users to explore 2024 sales performance by month, region, product category, and salesperson (via ID). Key metrics displayed include:

  _>>_ Total Sales

  _>>_ Highest Performing Region & Revenue

  _>>_ Average Monthly Sales

  _>>_ Category-Wise Breakdown

With interactive controls and clean visuals, this dashboard provides a dynamic, professional-grade analytics experience built entirely in Excel.





