# Hospital Admission & Discharge Analysis

##  Project Overview

This project analyzes hospital admission and discharge data to understand **patient admissions, discharge patterns, length of stay, patient outcomes, ICU stay, and 30-day readmissions**.

The project uses **MySQL for data cleaning, transformation, and analysis** and **Power BI for interactive dashboard development**.

The objective is to convert raw hospital data into meaningful healthcare insights that can support understanding of patient flow and hospital utilization patterns.

---

## 🎯 Objectives

- Analyze total hospital admissions and patient outcomes.
- Calculate average length of hospital stay.
- Analyze daily discharge patterns.
- Identify discharge trends across weekdays.
- Compare admissions and discharges across age groups.
- Compare admissions and discharges by gender.
- Analyze ICU length of stay by patient outcome.
- Identify patients readmitted within 30 days of discharge.
- Calculate the 30-day readmission rate.
- Analyze readmissions among patients with hypertension and diabetes.
- Develop an interactive Power BI dashboard for hospital data analysis.

---

## 📊 Dataset

The project uses a hospital admission dataset containing patient-level information related to:

- Patient/MRD number
- Date of admission
- Date of discharge
- Duration of stay
- Age
- Gender
- Patient outcome
- ICU duration
- Hypertension status
- Diabetes status
- Admission year
- Other patient-related attributes

### Dataset Summary

| Metric | Value |
|---|---:|
| Raw admission records | 14,620 |
| Records after duplicate removal | 13,339 |
| Total discharges | 12,008 |
| Average length of stay | 6 days |
| Average daily discharge | 16 |
| 30-day readmissions | 621 |
| 30-day readmission rate | 4.62% |

---

## 🛠️ Tools & Technologies

### SQL / MySQL
- MySQL
- Data Cleaning
- Data Transformation
- CTEs
- Window Functions
- `ROW_NUMBER()`
- `LAG()`
- Date Functions
- Aggregation
- Views

### Power BI
- Power Query
- Data Modeling
- DAX
- KPI Cards
- Slicers
- Donut Charts
- Line Charts
- Bar Charts
- Interactive Dashboard

### Other Tools
- GitHub
- CSV Dataset

---

## 🔄 Project Workflow

```text
Raw Hospital Dataset
        ↓
Data Inspection
        ↓
Data Type Checking
        ↓
Date Cleaning & Standardization
        ↓
Duplicate Detection & Removal
        ↓
Creation of Cleaned SQL Views
        ↓
Healthcare KPI Calculation
        ↓
Readmission Analysis
        ↓
Power BI Visualization
        ↓
Interactive Hospital Dashboard
