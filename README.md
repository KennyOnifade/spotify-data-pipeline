# 🎧 Spotify Data Pipeline & Analysis (Python + SQL Server)

## 📌 Overview
This project demonstrates a complete data pipeline built using Python and SQL Server.

The system:
- Loads raw Spotify song data from CSV
- Cleans and processes data using pandas
- Stores structured data in SQL Server
- Performs analytical queries using SQL

---

## 🛠️ Technologies Used
- Python (pandas, pyodbc)
- SQL Server (Docker)
- Jupyter Notebook
- VS Code

---

## ⚙️ Pipeline Architecture
CSV → Pandas → Data Cleaning → SQL Server → SQL Analysis

---

## 📊 Key Analysis

### 1. Songs added in March
- Identified records based on upload date

### 2. Maximum duration per year
- Grouped by release year

### 3. Artist productivity
- Counted number of songs per artist

### 4. 2010-specific analysis
- Filtered dataset for year-specific insights

### 5. Genre trends over time
- Grouped by genre and year

---

## 🚀 Additional Insights
- Top 10 longest songs
- Most popular genres

---

## 🧠 What I Learned
- Data cleaning using pandas
- SQL database design and normalization concepts
- Connecting Python to SQL Server using pyodbc
- Building end-to-end data pipelines

---

## 📸 Sample Output

### SQL Table Row Count
![SQL Count](screenshots/sql_count.png)

### SQL Sample Data
![SQL Data](screenshots/sql_top10.png)

### Pandas Analysis
![Pandas Output](screenshots/pandas_analysis.png)

---

## 🔮 Future Improvements
- Automate pipeline with scheduling
- Build dashboard (Power BI / Tableau)

---

## 👤 Author
Kehinde Onifade
