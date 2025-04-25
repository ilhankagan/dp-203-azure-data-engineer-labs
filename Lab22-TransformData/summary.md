# 🔄 Lab 22 - Transform Data Using Apache Spark

> [Lab Instructions](https://microsoftlearning.github.io/mslearn-databricks/Instructions/Exercises/LA-03-Transform-data.html)

## 📌 Objective  
Learn to clean, transform, and manipulate data using PySpark in Azure Databricks.

## 🛠️ Steps Performed  

### 1. 🧾 Load Data with Schema  
- Defined a custom schema for the sales dataset.  
- Loaded `.csv` files into a PySpark DataFrame using that schema.  
- ![table](./table.PNG)

### 2. 🚮 Remove Duplicates and Add Tax Column  
- Removed duplicates using `dropDuplicates()`.  
- Added a new column `Tax` calculated from `UnitPrice * 0.08`.  
- Converted `Tax` column to float type.  
- ![removedup](./removedup.PNG)

### 3. 📊 Group Data by Year  
- Used `year()` function to extract year from `OrderDate`.  
- Grouped data by year and counted orders.  
- ![grupbyyear](./grupbyyear.PNG)

### 4. 🎯 Select Specific Columns and Deduplicate  
- Selected only `CustomerName` and `Email` columns.  
- Displayed unique customer entries using `distinct()`.  
- ![spesific](./spesific.PNG)

## 🎯 Learnings  
- Applied schema definition while reading raw data.  
- Transformed and enriched data using PySpark functions.  
- Practiced real-time data aggregation and filtering techniques.  
- Cleaned and deduplicated datasets effectively.

---

✅ **Lab 22 completed!**  
🔗 GitHub Repo: [dp-203-azure-data-engineer-labs](https://github.com/ilhankagan/dp-203-azure-data-engineer-labs)

