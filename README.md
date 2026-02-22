# Company Performance Data Analysis 📊

This project focuses on cleaning, merging, and analyzing employee performance data using Python and Pandas.

## 🛠️ Tools & Libraries Used
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib (Visualization)
- **Environment:** Pydroid 3 / Jupyter Notebook

## 📋 Project Overview
The goal was to integrate two separate datasets containing employee details and their performance scores/salaries. I performed extensive data cleaning to ensure the accuracy of the final insights.

## 🚀 Step-by-Step Process

### 1. Data Cleaning
- **Employee IDs:** Standardized IDs by removing 'EMP' prefixes and stripping whitespace.
- **Name Cleaning:** Used Regex to remove numeric suffixes from names (e.g., 'Aisha1' -> 'Aisha').
- **Handling Missing Values:** - Missing Departments were filled with 'Unknown'.
  - Missing Salaries were imputed using the mean salary.
  - Performance scores were converted to numeric, treating 'Excellent' as 5.

### 2. Data Merging
- Performed an **Outer Join** on two datasets based on `Employee_ID` to ensure no employee record was lost.

### 3. Sorting & Final Export
- Sorted the combined data by `Employee_ID` and exported it to a multi-sheet Excel workbook.

## 💡 Key Insights
- **Top 5 Performers:** Identified the highest-scoring employees for rewards and recognition.
- **Departmental Salary Trend:** Generated a horizontal bar chart to compare average salaries across different departments.

## 📊 Visualization
![Department Salary Chart](Company_Performance_Chart.png)

---
*Created by  Inamul Hasan
