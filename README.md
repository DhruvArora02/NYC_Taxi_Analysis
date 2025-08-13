# 🚖 NYC Taxi Data Analysis with Databricks & PySpark  

This project analyzes NYC taxi trip data using **Databricks**, **PySpark**, and **Spark SQL** to showcase skills in big data processing, data engineering, and analytics. The notebook loads raw CSV data, cleans and transforms it, performs statistical analysis, and creates visualizations to uncover insights about taxi fares, trip distances, and popular pickup/dropoff locations.  

---

## 📂 Project Structure  
├── NYC_Taxi_Analysis.ipynb         # Main Databricks / Jupyter Notebook

├── data/nyc_taxi_data.csv          # Sample dataset

├── README.md                       # Project documentation

---

## 🚀 Features  
- **Data Ingestion:** Load CSV data into Spark DataFrames.  
- **Data Cleaning:** Convert timestamps, handle missing values, and format numeric fields.  
- **Feature Engineering:** Extract trip hour, day-of-week, and trip duration.  
- **Data Analysis:**  
  - Aggregations with PySpark DataFrame API.  
  - SQL-style analysis with Spark SQL.  
- **Visualizations:**  
  - Trip counts by hour of day.  
  - Average fare by pickup location.  

---

## 🛠️ Tech Stack  
- **Databricks Community Edition**  
- **Apache Spark / PySpark**  
- **Spark SQL**  
- **Pandas**  
- **Matplotlib**  

---

## 📊 Insights from the Analysis  
- Peak taxi demand occurs in the evening hours.  
- Central Park and JFK Airport have the highest average fares.  
- Most trips are under 10 miles and have 1–3 passengers.  

---

## 🖼️ Preview  
> Example charts generated from the analysis:

**Trip Counts by Hour**  
![Trip Counts](charts/trip_counts_by_hour.png)  

**Average Fare by Pickup Location**  
![Average Fare](charts/avg_fare_by_location.png)  

---

## 💡 Skills Demonstrated  
- Big Data Analysis with Apache Spark  
- Data Cleaning & Transformation  
- SQL Querying in Spark  
- Feature Engineering  
- Data Visualization with Matplotlib  
- Working in Databricks Environment  

---

## 📥 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/nyc-taxi-databricks.git
cd nyc-taxi-databricks
```

### 2️⃣ Open in Databricks
- Sign up for Databricks Community Edition.

- Create a new Notebook and set the default language to Python.

- Upload the NYC_Taxi_Analysis.ipynb file.

- Upload the CSV dataset to your Databricks workspace /FileStore/.

- Update the file path in the notebook if needed.

### 3️⃣ Run Locally (Optional)
Install dependencies:
```
pip install pyspark pandas matplotlib
```
Open Jupyter Notebook:

```
jupyter notebook
```
Load and run NYC_Taxi_Analysis.ipynb.

## 📌 Possible Improvements
- Integrate with real NYC TLC trip data API.

- Use Delta Lake for optimized storage.

- Build an interactive dashboard with Plotly or Power BI.
