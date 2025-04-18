# 📊 Lab 4 - Analyze Data in a Lake Database

> [Lab 4 Talimatları](https://github.com/secedit/dp-203-azure-data-engineer/blob/master/Instructions/Labs/04-Create-a-Lake-Database.md)

## 🛠️ What I Did

### 1. Created a Lake Database
- Created a **Lake Database** called `RetailDB`.
- Defined three tables: `Customer`, `Product`, and `SalesOrder`.
- Set up relationships between tables using **Lake Database Designer**.
- Specified the input folder from Azure Data Lake and data format (Delimited Text).
- 📸 *Screenshot:* `tablo.PNG`

### 2. Uploaded Data to Data Lake
- Uploaded a `.csv` file (`customer.csv`) to the Azure Data Lake using the workspace storage.
- 📸 *Screenshot:* `csvuplaod.PNG`

### 3. Queried CSV File with SQL Script
- Queried the uploaded `customer.csv` file using SQL in **Synapse Studio**.
- Verified the uploaded data with a basic `SELECT` query.
- 📸 *Screenshot:* `csvsql.PNG`

### 4. Queried Lake Database Table
- Ran a SQL query to fetch customer data from the `Customer` table in the Lake Database.
- Viewed results in tabular format to validate the schema and data.
- 📸 *Screenshot:* `sql.PNG`

### 5. Additional Query and Validation
- Executed an extended SQL script to check column mappings and data types.
- 📸 *Screenshot:* `sql2.PNG`
- 📸 *Screenshot:* `tablo.PNG`

---

✅ **Completed** Lab 4 successfully and learned how to:
- Create lake database and define schema
- Link Azure Data Lake storage
- Query structured data using Synapse SQL

