# Interswitch-Job_Shadowing-2.0
Excel for Data Analytics. An assessment project submitted during a training by Interswitch Group for the Job Shadowing 2.0 programme.
---

# Excel Data Analytics Project – HR Case Study

## Overview

This project demonstrates how Microsoft Excel can be used to clean data, analyze workforce information, and answer key business questions using built-in Excel functions. The analysis focuses on HR data to generate insights that support workforce planning, salary analysis, and employee performance evaluation.

The goal of the project is to showcase strong foundational data analytics skills using Excel, including data cleaning, logical analysis, and business-focused reporting.

---

## Dataset

The dataset contains employee-level HR information, including:

* Employee ID
* Department
* Salary
* Tenure
* Performance Score
* Hire Date

The data was provided in an Excel file and required cleaning before analysis.

---

## Tools

* **Microsoft Excel**

  * Data Cleaning
  * Excel Functions
  * Basic Aggregation & Analysis

---

## Steps

1. **Opened the Dataset**

   * Reviewed structure, columns, and data types
   * Identified missing values and inconsistencies

2. **Data Cleaning**

   * Removed duplicates
   * Handled missing and inconsistent entries
   * Standardized column formats (dates, numbers, text)

3. **Data Analysis Using Excel Functions**

   * Used functions such as:

     * `COUNT`, `COUNTA`
     * `SUM`, `AVERAGE`
     * `MAX`, `MIN`
     * `IF`
     * `COUNTIF`, `AVERAGEIF`
     * `XLOOKUP`, `ROUNDDOWN`
   * Grouped and analyzed data by department and performance metrics

4. **Answered Business Questions**

   * Total number of employees -239
     =COUNT(Dataset!A:A)
   * Employee count per department
     =COUNTIF(Dataset!G:G,'Task-Solution'!C2)
   * Total and average salary
     =SUM(Dataset!R:R), =AVERAGEIF(Dataset!G:G,'Task-Solution'!C2,Dataset!R:R)
   * Highest and lowest salaries
     =MAX(Dataset!R:R), =MIN(Dataset!R:R)
   * Employees with performance scores above 80
     =COUNTIF(Dataset!S:S,">80")
   * Average employee tenure
     =AVERAGE(Dataset!N:N)
   * Employee Age Range
     =XLOOKUP(H2,'Age Range'!A:A,'Age Range'!B:B)
   * Employee Lenght of Stay (LOS) Range
     =XLOOKUP(N2,'LOS Range'!A:A,'LOS Range'!B:B)
     
---

## Results

Key insights generated from the analysis include:

* Clear visibility into workforce size and departmental distribution
* Salary trends across departments
* Identification of high-performing employees
* Insights into employee tenure and retention patterns

These findings can support HR decision-making, budgeting, and workforce planning.

---

## How to Run

1. Download or clone this repository
2. Open the Excel file using **Microsoft Excel**
3. Review the cleaned dataset and analysis sheets
4. Explore formulas and calculations used to answer each business question

No additional tools or installations are required.

---

### Author

**Taiwo Adeyemi**
*Data Analyst | Excel | SQL | Python | Power BI*

---
