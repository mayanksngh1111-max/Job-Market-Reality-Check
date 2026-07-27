# 📊 Job Market Reality Check – Data Analyst Jobs Analysis

## 📌 Project Overview:

The **Job Market Reality Check** project is an end-to-end Data Analytics project that analyzes real-world **Data Analyst job postings** to identify in-demand skills, salary trends, hiring locations, and industry insights.
The project demonstrates the complete data analytics workflow—from data cleaning and preprocessing using Python, storing cleaned data in PostgreSQL, performing SQL analysis, and creating interactive dashboards in Power BI.


## 🎯 Problem Statement:

The demand for Data Analysts is growing rapidly, but job seekers often struggle to identify which technical skills, tools, and locations offer the best career opportunities.

This project analyzes real-world job postings to answer questions such as:

- Which skills are most in demand?
- Which skills lead to higher salaries?
- Which cities have the highest hiring demand?
- Which industries hire the most Data Analysts?
- What salary trends exist across different locations?

---

## 🛠 Technologies Used:

- Python
- Pandas
- NumPy
- Regular Expressions (Regex)
- PostgreSQL
- SQL
- Excel
- Power BI
- Git & GitHub
- PyCharm

---

## 📂 Dataset

The dataset contains over **2,200 Data Analyst job postings** with information such as:

- Job Title
- Company Name
- Salary Estimate
- Company Rating
- Location
- Industry
- Sector
- Revenue
- Company Size
- Job Description
- Headquarters

---

## ⚙️ Project Workflow:

### 1. Data Collection

- Imported CSV dataset into Python using Pandas.

### 2. Data Cleaning

- Removed duplicate records
- Removed missing values
- Standardized column names
- Cleaned salary estimates
- Extracted average salary
- Split city and state

### 3. Feature Engineering

Created new columns:

- Job ID
- Average Salary
- Average Revenue
- City
- State
- Extracted Skills

### 4. Skill Extraction

Used Python Regular Expressions to identify skills from job descriptions.

Examples:

- Python
- SQL
- Excel
- Power BI
- Tableau
- AWS
- Azure
- Spark
- Hadoop
- Machine Learning
- Statistics
- ETL

---

## 🗄 Database

The cleaned dataset was imported into PostgreSQL using SQLAlchemy.

Tables:

- job
- job_skills

---

## 📈 SQL Analysis

Some business questions answered:

- Top in-demand skills
- Average salary by skill
- Highest paying cities
- Highest paying industries
- Jobs by company size
- Salary by company rating
- Most common skill combinations

---

## 📊 Power BI Dashboard

The dashboard includes:

- KPI Cards
- Total Jobs
- Average Salary
- Average Company Rating
- Top Skills
- Salary by Skill
- Top Hiring Cities
- Jobs by Industry
- Salary Distribution
- Interactive Filters

---

## 📁 Project Structure

```
Job-Market-Reality-Check/
│
├── Data/
│   ├── DataAnalyst.csv
│   ├── jobs_cleaned.csv
│   └── job_skills.csv
│
├── Python/
│   └── data_cleaning.py
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── Job_Market_Dashboard.pbix
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Job-Market-Reality-Check.git
```

### Install Libraries

```bash
pip install pandas numpy sqlalchemy psycopg2-binary
```

### Run Python Script

```bash
python data_cleaning.py
```

### Load Data into PostgreSQL

The script automatically imports the cleaned data into PostgreSQL.

### Execute SQL Queries

Run the SQL queries provided in the **SQL** folder.

### Open Power BI Dashboard

Open the `.pbix` file to explore the dashboard.

---

## 📌 Key Insights

- SQL is one of the most demanded skills.
- Python appears in the majority of Data Analyst job postings.
- Power BI and Tableau are highly valued visualization tools.
- Jobs requiring cloud platforms (AWS, Azure) generally offer higher salaries.
- Major cities provide the highest number of opportunities.

---

## 📷 Dashboard Preview

*(Add screenshots of your Power BI dashboard here.)*

Example:

```
Dashboard_Screenshot.png
```

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Regular Expressions
- SQL
- PostgreSQL
- Data Visualization
- Power BI
- Exploratory Data Analysis (EDA)
- Business Intelligence

---

## 👨‍💻 Author

**Mayank Singh**

Engineering Student | Aspiring Data Analyst




