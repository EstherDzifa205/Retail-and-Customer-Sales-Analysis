
# Retail-Sales-Customer-Analysis
This is a project to analyse the relationship between customer demographics and the products they purchase at a retail store. KPI's were achieved through data cleaning, feature engineering and visualization

# 1. Project Overview
**Retail Dataset** (Transaction ID, Customer ID, Item Quantity, Age, Unit, Total Amount) The objective is to create an **interactive Dashboard in Excel** that answers;
*  Which product Category generate the most revenue?
*  What age group gives the most revenue
*  Which month did sales peak
*  The average age of a customer

# 2. Data Understanding
 * Dataset description: 
     Number of records: 1,000
     Number of columns: 10
 * Key fields: Transaction ID,  Date, Gender, Age, Product category,Quantity, Price per unit, Total Amount 
 * Limitations: The sample size was small, there were missing month

# 3. Methodology
# i.Data Cleaning (Excel)
 * Removed duplicates, checking for missing values, filters and inconsistences.  
*  Standardized dates, product and region names.
# ii. Feature Engineering (Excel)
 * Created a new column: Age group to include an age range. **Age Group** = **=IF(AND(F2>=18,F2<=29),"Youth",IF(AND(F2>=30,F2<=49),"Young     Adult",IF(AND(F2>=50,F2<=64),"Adult",""))).**
# iii. Data Analysis (Excel)
Exploratory analysis: Pivot tables to summarize sales by product category, sales by gender and sales by age group, Charts to spot trends:
 *  Sales ↔ Gender
 *  Sales ↔ Age Group
Sales ↔ Category :
*  Total Sales
*  Average Age
*  Monthly Sales
* Customer Count
* Total Quantity sold
# iv.Visualization (Excel)
  Dashboard 1: **Sales Overview**
  Dashboard 2: **Sales by Male Gender**
  Dashboard 3: **Clothing Category and Male Gender Insights**
  Dashboard 4: **Clothing Category, Male Gender and Young adult group Insights**

# 4.The Dashboards







![WhatsApp Image 2025-10-28 at 22 47 18 (3)](https://github.com/user-attachments/assets/05355c8c-b563-4b7f-921c-2f5b5d27fc6c)











# Sales Overview
*  **Total Sales**: 456K
*  **Sales by Categories**: Beauty (143.52k) > Clothing (155.58K) > Electronics (156.91K)
*  **Gender Contribution**: Male (49%), Female (51%)
*  **Monthly Trends**: Peak in May (53.15K), dip in September (23.62K)







![WhatsApp Image 2025-10-28 at 22 47 18 (4)](https://github.com/user-attachments/assets/5c3200d5-81ac-44de-882d-9dd7d6fc62db)












# Sales By Gender
* **Top Revenue**: (23.8K, 1298 units)
* **Revenue by Category**: Beauty (74.83k) > Clothing (81.28K) > Electronics (76.74K)
* **Average Female Customer Age**: 41
* **Monthly Quantity Trend**: Peak in October (26.6k)




# Clothing Category and Male Gender Insights
# Clothing Category, Male Gender and Young adult group Insights









![WhatsApp Image 2025-10-28 at 22 47 18 (2)](https://github.com/user-attachments/assets/0d4077e7-ea58-40ff-94a9-c8343c8c4e5b)












# 5. Key Insights
* **Electronics dominate** sales, (34.41%).
* **Young Adult Customer group** bring the most revenue, churning 189.69K.
* Sales are **seasonal**, peaking in May across both revenue and quantity.

# 6. Recommendations
*  **Expand Electronics to include smart phones, tablets, smart watches, game consoles**, etc. to sustain revenue growth.
*  **Target female dominated demographics** with tailored marketing campaigns to generate more revenue from the female customers since          they contribute a high margin of sales.
*  I**mprove customer diversity** by broadening your offerings to appeal to different customers, age groups and lifestyles.

# 7. Conclusion
This project shows how structured analysis of **Sales, Product, and Customer data** using Excel can generate clear business insights.
It demonstrates **end-to-end analytics workflow.**

# 8. Tool; Excel & Tech Flow
* *Data Cleaning*
* *Feature Engineering*
* *Pivot tables*
* *Visualization*





