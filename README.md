# 🌄 West Virginia Economic Trends – NewForce Insights Project

![Python](https://img.shields.io/badge/Python-Data_Cleaning-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Processing-150458?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-IDE-007ACC?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-Data_Storage-34A853?style=for-the-badge\&logo=google-sheets\&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-Visualization-FF6F00?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Version_control-181717?style=for-the-badge\&logo=github\&logoColor=white)

---

## 📋 Table of Contents

* 🎯 Motivation
* ❓ Key Questions
* 🔧 Acquiring & Cleaning the Data
* ⚠️ Challenges Encountered
* 📊 Analysis & Presentation
* 🛠️ Technologies Used
* 📚 Sources

---

## 🎯 Motivation

Understanding **West Virginia’s economic trends** is vital for informing policymakers, businesses, and citizens about the health of the state’s labor market, industries, and overall economic performance.

This project focuses on:

* Labor market performance (employment/unemployment trends)
* Industry employment shifts (BLS CES & LAUS data)
* Gross Domestic Product patterns (BEA data)

By combining multiple datasets, this project provides a **data-driven snapshot of West Virginia’s economy** and insights for decision-making.

---

## ❓ Key Questions

**Primary Question**
💡 What are the main trends in West Virginia’s economy over time and how do industries compare?

**Supporting Questions**
📈 How has employment changed across key industries?
📉 What are the patterns in unemployment rates over time?
💰 How does GDP growth compare across sectors and counties?
🏭 Which industries are growing or shrinking?
🌐 How can insights from this data guide future economic policy?

---

## 🔧 Acquiring & Cleaning the Data

### 📦 Data Sources

* **BLS CES (Current Employment Statistics)** – Industry employment data
* **BLS LAUS (Local Area Unemployment Statistics)** – Unemployment data
* **BEA (Bureau of Economic Analysis)** – State GDP and regional economic data
* **WVSOS Business Registrations** – State-level business formation data

### 🧹 Cleaning & Normalization Steps

* Standardized column names and removed extra whitespace
* Filtered for **West Virginia** and relevant geographies
* Converted dates to consistent formats for time series analysis
* Reordered columns for clarity and merged related datasets
* Ensured numeric types were correct for calculations and analysis
* Pivoted or “melted” data as needed for clean visualization
* Loaded cleaned datasets into **Google Sheets** for validation
* Final data uploaded to **Looker Studio** for presentation and dashboards

---

## ⚠️ Challenges Encountered

* Inconsistent date formats across datasets 📅
* Missing or sparse data for certain counties and years 🕳️
* Duplicate rows in some datasets, requiring careful de-duplication 🧹
* Differences in industry classification across BLS and BEA data 🏭
* Harmonizing state vs county-level data for unified analysis 🌐

---

## 📊 Analysis & Presentation

* **Data Cleaning & Exploration**: Conducted in **Python** using **Pandas** in VS Code/Anaconda
* **Data Validation & Storage**: Used **Google Sheets** for intermediate cleaning and review
* **Visualization & Reporting**: Created dashboards in **Looker Studio** for presentation-ready insights
* **Insights Delivered**: Showed trends in employment, unemployment, GDP, and business formation across West Virginia

---

## 🛠️ Technologies Used

* **Python** – Data cleaning and exploration (Pandas, NumPy)
* **VS Code / Anaconda** – IDE and environment for Python workflows
* **Google Sheets** – Data review and intermediate storage
* **Looker Studio** – Interactive dashboards and presentation visualization
* **Git / GitHub** – Version control and project management

---

## 📚 Sources

* **Bureau of Labor Statistics (BLS)** – CES and LAUS data
* **Bureau of Economic Analysis (BEA)** – GDP data
* **West Virginia Secretary of State (WVSOS)** – Business registration data

---

## 👨‍💻 Author

**Brandon Gray**
Data Analyst / Full Stack Developer