# San_Francisco_Salary_Analysis-


## 📌 Problem Statement

The San Francisco City Employee Salary dataset (2011–2014) contains payroll records for over 148,000 employees across a wide range of job titles. Due to its large size and complex payroll structure, extracting meaningful insights directly from the raw data is difficult.

The dataset also contains missing values, inconsistent text formatting, duplicate records, and unnecessary columns, which affect data quality and analysis. These issues must be addressed before reliable analysis can be performed.

A structured data cleaning process is therefore required to prepare the dataset for accurate exploratory data analysis (EDA) and meaningful business insights


## 🎯 Project Objectives

* Clean and preprocess the raw payroll dataset to improve data quality and prepare it for analysis.
* Analyze employee compensation, including Base Pay, Overtime Pay, Benefits, Total Pay, and Total Pay & Benefits.
* Identify the highest-paid and lowest-paid employees and job titles.
* Examine year-wise payroll trends and workforce distribution from 2011 to 2014.
* Analyze overtime and benefits to understand their contribution to overall employee compensation.
* Detect salary outliers and evaluate whether they represent valid business cases or potential anomalies.
* Generate meaningful business insights and recommendations to support payroll analysis and workforce planning.

## 📊 Dataset Description

| Feature | Details |
|----------|---------|
| **Dataset Name** | San Francisco Employee Salaries |
| **Source** | Kaggle |
| **Time Period** | 2011–2014 |
| **Total Records** | 148,654 Employee Salary Records |
| **Total Columns (Before Cleaning)** | 13 |
| **Key Features** | EmployeeName, JobTitle, BasePay, OvertimePay, OtherPay, Benefits, TotalPay, TotalPayBenefits, Year, Agency |
| **Columns Removed** | Notes, Status (More than 99% missing values) |


## 🛠️ Tools & Libraries Used

| Tool / Library       | Purpose                                                                 |
| -------------------- | ----------------------------------------------------------------------- |
| **Python**           | Core programming language used for data analysis.                       |
| **Pandas**           | Data loading, cleaning, transformation, and analysis.                   |
| **NumPy**            | Numerical computations and array operations.                            |
| **Matplotlib**       | Data visualization and chart customization.                             |
| **Seaborn**          | Statistical data visualization and exploratory analysis.                |
| **Jupyter Notebook** | Interactive environment for data cleaning, analysis, and visualization. |





## 📈 Key Findings & Insights

* **Salary Distribution:** Most employees earn salaries in the lower to middle salary range, while only a few employees receive exceptionally high compensation.

* **Year-wise Highest Salaries (2011–2014):**

  * **2011:** Edward Harrington — **$294,580**
  * **2012:** Gregory Suhr — **$302,578**
  * **2013:** Gregory P. Suhr — **$319,275**
  * **2014:** Amy P. Hart — **$318,835**

* **Highest Paying Job Titles:**

  * Chief Investment Officer — **$436,224**
  * Chief, Fire Department — **$408,865**
  * General Manager (Metropolitan Transit Authority) — **$399,211**
  * General Manager (Public Transport Department) — **$380,696**
  * Chief of Police — **$375,797**

* **Overtime Insights:** Around **48%** of employees received overtime pay, while **52%** did not. The highest overtime payments were recorded for roles such as **Captain III (Police Department)**, **Lieutenant (Fire Suppression)**, and **Deputy Sheriff**.

* **Lowest Salary Employees:** The analysis identified employees with **Total Pay Benefits of $0.00**. For presentation purposes, only the **top 10 records** are shown in the notebook.

* **Top 10 Overtime Earners:** The analysis highlights the **top 10 employees** with the highest overtime payments. Most belong to **Police**, **Fire**, and **Sheriff** departments.

* **Employees with Overtime Pay Lower than Benefits:** Several employees received **higher benefits than overtime pay**, indicating that their total compensation relied more on benefits than overtime earnings.

* **Employees with Zero Base Pay but Receiving Benefits:** A small number of employees were found with **zero Base Pay** while still receiving **Benefits**. These records may represent special payroll cases, part-time employment, or other compensation arrangements and may require further review.


💡Recommendations
Review high overtime departments such as Police, Fire, and Sheriff to understand the reasons for consistently high overtime payments and explore workforce planning opportunities.
Monitor high salary outliers regularly to ensure employee compensation is aligned with job responsibilities and organizational pay policies.
Review payroll records where employees have zero Base Pay but receive Benefits to verify that these records are accurate and follow payroll guidelines.
Analyze job roles with the highest compensation to better understand salary structures and support future budgeting decisions.
Track salary trends every year to evaluate payroll growth and improve long-term financial planning.
Perform regular data quality checks to identify missing values, inconsistent records, and formatting issues before payroll analysis.


