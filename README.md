# 🌊 Flood Analysis using PySpark, SQL & Matplotlib  

## 📌 Project Overview  
This project analyzes **flood data from NDMA (National Disaster Management Authority Pakistan)** using **PySpark, SQL, and Python**.  
It demonstrates a simple **ETL pipeline** and generates insights such as the most affected regions and top 5 regions with houses damaged.  

---

## ⚙️ ETL Pipeline  

### 1. **Extract (E)**  
- Imported NDMA dataset into Google Colab using **PySpark**.  

### 2. **Transform (T)**  
- Cleaned and aggregated the dataset.  
- Used **SQL queries on Spark** to:  
  - Calculate total affected population by region.  
  - Identify **Top 5 regions with most houses damaged**.  

### 3. **Load (L)**  
- Loaded the transformed results into **Pandas DataFrame**.  
- Visualized insights using **Matplotlib (bar charts)**.  

---

## 📊 Visualizations  
- **Affected Population by Region**  
- **Top 5 Regions with Houses Damaged**  

Following were the results:  

![Affected Population](https://github.com/Chrisstinaa7/flood_analysis/blob/main/Pakistan_Floods/charts/total_affected_population.png)  
![Top 5 Houses Damaged](https://github.com/Chrisstinaa7/flood_analysis/blob/main/Pakistan_Floods/charts/top5_houses_damaged.png)  

---

## 🚀 Tech Stack  
- **PySpark** – for distributed data processing  
- **SQL** – for querying and transformations  
- **Python (Pandas, Matplotlib)** – for analysis & visualization  
- **Google Colab** – development environment  

---

## 📂 Project Structure 
- Pakistan_Floods/
- ├── README.md # Project documentation
- ├── Pakistan_Floods.ipynb # Jupyter/Colab notebook with analysis
- ├── charts/ # Visualization outputs
- │ ├── total_affected_population.png
- │ └── top5_houses_damaged.png
  
## 📌 Future Improvements  
- Automate data ingestion from NDMA’s live updates.  
- Deploy pipeline on **Azure** using **Databricks**.  
- Store results in a **data warehouse** (Snowflake/Redshift).  

---

✨ *This project is part of my journey to become a Data Engineer. Feedback is always welcome!*
