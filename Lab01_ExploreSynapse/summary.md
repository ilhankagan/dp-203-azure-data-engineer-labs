# Lab 1: Explore Azure Synapse

In this lab, I explored how to query and analyze data in a data lake using both serverless SQL and Apache Spark in **Azure Synapse Analytics**.

---

## 🔍 What I Did

### 1. Queried Data with Serverless SQL Pool
- Used **OPENROWSET** to read external data from CSV files stored in Azure Data Lake.
- Wrote a SQL query to select the top 100 rows from the dataset.
- Created a **line chart** and a **column chart** in Synapse Studio to visualize product pricing data.
- 📸 ![SQL Query Chart](./SQL.PNG)

### 2. Analyzed Data with PySpark
- Used PySpark inside a Synapse notebook to read the same dataset.
- Filtered and grouped the data by product categories using Spark DataFrame methods.
- Counted product frequency and visualized it using Spark-compatible charting tools.
- 📸 *Screenshot:* `pyspark_sorgu.PNG`

### 3. Aggregated Data with GroupBy Queries
- Used SQL to group products and summarize data with `GROUP BY` and `COUNT()` functions.
- 📸 *Screenshot:* `SORGU_BY_GROUP_2.PNG`

---

## 🧠 Why It Matters

- Demonstrated how **Synapse’s serverless SQL pool** can efficiently read and analyze file-based data without needing to load it into a traditional database.
- Showed how **Apache Spark** is used for large-scale data processing within notebooks.
- Learned the difference between working with structured (SQL) and distributed (Spark) compute environments.
