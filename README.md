# Exploratory Data Analysis (EDA) - Layoffs Dataset

## 📌 Project Overview
After performing data cleaning, this project focuses on **Exploratory Data Analysis (EDA)** to derive insights from the layoffs dataset. The dataset contains records of company layoffs, including industry, country, funding raised, and more. The objective of this project is to analyze trends and patterns in layoffs across different factors such as time, industry, and company size using **MySQL**.

## 🧠 Business Problem  
Mass layoffs affect both the economy and individual livelihoods. During financial downturns, it's crucial to identify:  
- Which industries and countries are most impacted  
- What funding stages face higher risks  
- How layoff trends evolve over time  

This project aims to extract actionable insights from layoff data to support **HR strategists, policymakers, investors, and analysts** in workforce planning and economic forecasting.

## 💥 Business Impact  
- 📊 Helps businesses and governments **predict economic stress** across industries  
- 💼 Supports **strategic hiring and downsizing** decisions for HR departments  
- 🌍 Reveals **region-wise vulnerabilities** to help mitigate future workforce crises  
- 💡 Offers insights to **investors and market analysts** by connecting layoffs with company funding stages and raised capital

## ✅ Solution  
This project performs SQL-based EDA to analyze:
- 🔍 **Maximum layoffs** by company and percentage  
- 🏢 **Companies with 100% workforce cuts**  
- 📆 **Layoff trends over time** (year/month)  
- 🏭 **Industry-wise impacts**  
- 🌐 **Country-wise analysis**  

All insights were derived using structured SQL queries (e.g., `GROUP BY`, `ORDER BY`, `MAX()`, `WHERE`) and optionally visualized using Python (Jupyter).

## 📊 Dataset Information
- **Source:** Cleaned version of `layoffs.csv`
- **Total Entries:** 2,361 rows
- **Columns:** 9
  - `company`: Name of the company
  - `location`: Company headquarters
  - `industry`: Industry category
  - `total_laid_off`: Number of employees laid off
  - `percentage_laid_off`: Percentage of workforce laid off
  - `date`: Layoff announcement date
  - `stage`: Funding stage of the company
  - `country`: Country of the company
  - `funds_raised_millions`: Total funds raised in millions

## 🔍 Key Analysis Steps
### 1️⃣ Identifying Maximum Layoffs
- Found the **maximum number of employees laid off** and the **highest percentage of workforce reduction** in a single instance.

### 2️⃣ Companies with 100% Layoffs
- Identified companies where **100% of employees** were laid off.
- Analyzed which companies had the most severe layoffs in terms of absolute numbers and funding raised.

### 3️⃣ Layoffs by Company
- Aggregated **total layoffs per company** to find which firms had the highest job cuts.

### 4️⃣ Layoff Trends Over Time
- Found the **earliest and latest layoffs** recorded in the dataset.
- Grouped layoffs by **year and month** to identify layoff trends over time.

### 5️⃣ Industry-Wise Analysis
- Identified industries with the **highest total layoffs**.
- Determined which industries were most affected during layoffs.

### 6️⃣ Country-Wise Analysis
- Aggregated layoffs by **country** to find which nations were most impacted.
- Compared layoffs across different regions.

## 💻 Technologies Used
- **MySQL** – Used for executing EDA queries and aggregating insights.
- **Jupyter Notebook / Python (Optional)** – Could be used for further visualization.

## 📜 SQL Queries Used
This analysis was conducted using **SQL queries**, including:
- `MAX()` – To find the highest number of layoffs.
- `GROUP BY` – To aggregate layoffs by company, industry, country, and time.
- `ORDER BY` – To rank layoffs based on total numbers.
- `WHERE` – To filter specific conditions such as **100% workforce layoffs**.

## 📌 Why This Project?
EDA is a crucial step in **data science** and **decision-making**. By analyzing layoffs, we can:
- Identify which industries are most affected.
- Detect economic trends and corporate downsizing patterns.
- Provide data-driven insights for workforce planning and policy-making.

## 🚀 How to Use This Repository
1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/your-username/data-analysis-project.git
