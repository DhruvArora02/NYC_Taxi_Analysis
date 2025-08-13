
# NYC Taxi Analysis - Databricks Pro Project

## 📌 Project Overview
This project demonstrates how to use **Databricks** and **PySpark** for big data analytics, SQL queries, Delta Lake storage, machine learning with MLlib, and visualizations — using **NYC Taxi data**.

## 🚀 Features
- **ETL with PySpark**: Clean and transform raw taxi trip data.
- **Delta Lake**: Store processed data in a fault-tolerant format.
- **SQL Queries**: Run analytics queries directly in Databricks.
- **Data Visualization**: Use Matplotlib & Seaborn for insights.
- **MLlib Model**: Predict taxi fares using linear regression.

## 📂 Dataset
- `data/sample_nyc_taxi.csv` — Small dataset for quick testing.
- Optional: Download full **NYC Yellow Taxi dataset**:

```python
import urllib.request
url = "https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2024-01.parquet"
urllib.request.urlretrieve(url, "data/yellow_tripdata_2024-01.parquet")
```

## 🛠️ How to Run
Clone this repository:
```
git clone https://github.com/yourusername/nyc-taxi-databricks-pro.git
cd nyc-taxi-databricks-pro
```

Upload to Databricks or run locally with PySpark.

Open and run nyc_taxi_analysis_pro.ipynb step-by-step.

## 📊 Example Output
- Average Fare by Pickup Location bar chart.

- Fare prediction with MLlib.

## 📌 Technologies Used
- Databricks
- PySpark
- Delta Lake
- Spark SQL
- Matplotlib / Seaborn
- MLlib (Linear Regression)

## 🧠 Key Learnings
- Working with big data using PySpark DataFrames
- Creating Delta Lake tables for versioned, reliable storage
- Writing Spark SQL queries inside Databricks
- Building a machine learning model with Spark MLlib

## 📅 Future Improvements
- Add streaming data ingestion (Kafka or Spark Structured Streaming)
- Deploy ML model as an API endpoint
- Automate pipeline with Databricks Jobs
