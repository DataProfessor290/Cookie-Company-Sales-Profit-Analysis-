# Data Cleaning and Profit Analysis  Project

## Project Overview
This project analyzes profit distribution across different countries and product categories for the years 2019 and 2020. It provides insights into sales trends, profitability, and recommendations for improving revenue. The analysis was performed using pivot tables and pivot charts, with the findings presented in an interactive dashboard.

## Date: March 3, 2025  
**Author:** Tolulope Emuleomo

---

## Data Cleaning Procedure

### **Objective**
Ensure data integrity, consistency, and proper formatting for accurate analysis and SQL storage.

### **Steps:**

1. **Duplicate the Dataset**
   - Created a copy of the original dataset to preserve raw data and prevent accidental modifications.
   - Worked exclusively on the duplicate to ensure data integrity.

2. **Check for Missing Values and Duplicate Rows**
   - Scanned the dataset for missing values and confirmed no data gaps exist.
   - Checked for duplicate rows and ensured no redundant records.
   - Since no missing values or duplicates were found, proceeded with further processing.

3. **Ensure "Unit Sold" Column Contains Integers**
   - Converted the "Unit Sold" column to an integer (int) data type.
   - Handled any non-integer values if necessary.

4. **Convert "Revenue," "Cost," and "Profit" Columns to Numeric Format**
   - Ensured "Revenue," "Cost," and "Profit" columns were numeric (float or decimal).
   - Removed any non-numeric characters (e.g., currency symbols or text errors).
   - Converted the cleaned data to a numeric format suitable for SQL storage.

5. **Convert the "Date" Column to Datetime Format**
   - Standardized the "Date" column by converting it to a datetime data type.
   - Ensured all values followed a consistent date format (YYYY-MM-DD or equivalent).
   - Handled any incorrect or inconsistent date entries.

6. **Extract Month Name from "Date" Column**
   - Created a new "Month Name" column by extracting the month’s full name (e.g., "January").

7. **Create a Table for Analysis**
   - After duplicating the dataset, a table was created using the data array to facilitate pivot table and dashboard creation.

---

## Profit Analysis Report by Country and Product (2019-2020)

### **Summary of Findings:**

1. **Average Profit:**
   - The overall average profit from all countries and products is **3,947.66**.

2. **Country-wise Average Profit Distribution:**
   - **India:** 4,330.94 (Highest)
   - **United Kingdom:** 4,250.51
   - **United States:** 4,101.13
   - **Malaysia:** 3,534.28
   - **Philippines:** 3,521.46 (Lowest)

3. **Product-wise Average Profit Contribution:**
   - **Chocolate Chip:** 5,023.41 (Highest revenue-generating product)
   - **White Chocolate Macadamia Nut:** 4,842.98
   - **Oatmeal Raisin:** 4,626.49
   - **Snickerdoodle:** 3,947.55
   - **Sugar:** 2,709.88
   - **Fortune Cookie:** 1,326.46 (Lowest contribution)

---

## **Insights on Unit Sales Across Months:**

1. **Overall Average Sales:** 1,608 units

2. **Peak Sales Months:**
   - **April:** 2,254 units (Highest)
   - **July:** 1,982 units
   - **January:** 1,938 units

3. **Lowest Sales Months:**
   - **June:** 1,476 units (Lowest)
   - **December:** 1,479 units
   - **May:** 1,479 units

4. **Possible Seasonal Trends:**
   - Higher sales in **April and July** suggest strong seasonal demand, which could be leveraged for promotional campaigns.
   - The dip in **June and December** may require targeted strategies such as discounts or special promotions to boost sales.

---

## **Insights on Profit Across Months:**

1. **Overall Average Profit:** 3,947.66

2. **Highest Profit Months:**
   - **April:** 5,621.88 (Highest revenue period)
   - **July:** 4,969.53
   - **January:** 4,894.79

3. **Lowest Profit Months:**
   - **October:** 3,460.62 (Lowest profitability month)
   - **June:** 3,583.08
   - **May:** 3,624.48

4. **Profitability Trends:**
   - The highest profit months align with peak sales periods, particularly in **April and July**.
   - The months with lower unit sales (**June, October, and May**) also tend to show lower profits, suggesting a direct correlation between sales volume and revenue generation.

---

## **Insights and Recommendations:**

- **Focus on High-Performing Products:** Chocolate Chip and White Chocolate Macadamia Nut are the top profit generators. Increasing marketing efforts and distribution expansions in these categories could boost revenue.
- **Country-Specific Strategies:** India and the United Kingdom lead in average profits. Expansion strategies and targeted marketing in these regions may further increase sales.
- **Address Underperforming Products:** Fortune Cookie has the lowest revenue among all products. A detailed analysis is needed to determine if it should be discontinued or marketed differently.
- **Explore Growth Opportunities in the Philippines and Malaysia:** These countries have the lowest overall profits, presenting potential areas for business development.
- **Adjust Sales Strategies by Month:**
  - Given the strong sales in **April and July**, seasonal promotions should be utilized to maximize revenue.
  - **Targeted discounts** or marketing campaigns in **June and December** may help sustain revenue.
- **Leverage Profitability Data:**
  - Increasing stock availability and promotional activities in **April and July** can maximize revenue.
  - Strategic pricing or discounts in lower-profit months (**June, October, and May**) may improve profitability.
- **Implement Promotional Strategies:**
  - Launch **limited-time discounts**.
  - **Bundle popular products** with low-performing ones.
  - Utilize **digital marketing campaigns** to boost awareness and drive purchases.
- **Optimize Inventory Management:** Ensure peak sales months have sufficient stock to meet demand while minimizing excess inventory during slow months.
- **Strengthen Customer Engagement:** Implement **loyalty programs** and **personalized marketing strategies** to retain customers during slow months and encourage repeat purchases.

---

## **Conclusion**
The profit and sales analysis highlights strong performance from specific products and countries, as well as seasonal trends in unit sales and profitability. **Strategic marketing, resource allocation, and expansion in underperforming areas** can optimize profits further. A deeper dive into **consumer preferences and market trends** will be beneficial for sustained growth.

---

## **Tools Used**
- **Excel Pivot Tables & Pivot Charts** (for data analysis and visualization)
- **SQL** (for structured data storage)
- **Interactive Dashboard** (for data presentation and insights)

### **Author:** Tolulope Emuleomo  
📅 **Date:** March 3, 2025
