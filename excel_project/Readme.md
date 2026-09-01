# 📊 Employee Attendance Data Analysis – Excel

## 📌 Project Overview

This project focuses on **cleaning, analyzing, and visualizing employee attendance data using Microsoft Excel**.

The dataset contains employee attendance records, including employee information, attendance dates, departments, shifts, check-in/check-out times, and attendance status.

The project demonstrates a complete **Excel Data Analysis workflow**, from raw data cleaning to Pivot Tables, Dashboard creation, and business insights.

---

## 📁 Dataset Information

The original dataset contains **300 employee attendance records** with the following columns:

| Column              | Description                                        |
| ------------------- | -------------------------------------------------- |
| `Employee_ID`       | Unique employee identifier                         |
| `Attendance_Date`   | Date of attendance                                 |
| `Department`        | Employee department                                |
| `Shift`             | Employee work shift                                |
| `Check_In`          | Employee check-in time                             |
| `Check_Out`         | Employee check-out time                            |
| `Attendance_Status` | Attendance status such as Present, Absent, or Late |

After the data cleaning process, **261 valid records** remained for analysis.

---

## 🧹 Data Cleaning

The raw attendance data was reviewed and cleaned to improve data quality and consistency.

### Main Cleaning Steps

* Removed duplicate records
* Removed records with critical missing values
* Standardized department names
* Standardized shift names
* Corrected inconsistent shift assignments using check-in times
* Standardized Check-In and Check-Out time formats
* Standardized attendance status capitalization
* Handled missing values appropriately
* Created a corrected shift column for validation

### Data Quality

**Original records:** 300
**Clean records:** 261
**Removed records:** 39

---

## 📊 Excel Analysis

Several Excel features were used to analyze the cleaned attendance data.

### Pivot Tables

### 📊 Pivot Tables

Pivot Tables were created to analyze the following employee attendance patterns:

#### 1. Attendance Status by Department

<img width="752" height="452" alt="Attendance Status by Department" src="https://github.com/user-attachments/assets/911c940d-bf0c-4638-83fa-e081ac90df1b" />

**Interpretation:**
The Pivot Table shows the distribution of attendance statuses across different departments. **IT has the highest number of attendance records**, with Present being the dominant attendance status. Other departments, including Operations, Finance, Sales, Administration, and HR, also show Present as the most common status. The table also highlights differences in Late and Absent records between departments, which can help identify departments that may require closer attendance monitoring.

---

#### 2. Employees by Department

<img width="752" height="452" alt="Employees by Department" src="https://github.com/user-attachments/assets/98620e5d-5581-41e3-8d93-d831545e665d" />

**Interpretation:**
The Pivot Table shows the number of employee attendance records by department. **IT has the largest number of records**, followed by Operations and Finance, while HR has the smallest number of records. This indicates that IT represents the largest department in the analyzed attendance dataset, whereas HR represents the smallest.

---

#### 3. Attendance by Shift

<img width="752" height="452" alt="Attendance by Shift" src="https://github.com/user-attachments/assets/95ffb4a1-fcac-4fd3-827c-49880852a0bb" />

**Interpretation:**
The Pivot Table compares attendance records between the **Morning and Evening shifts**. The Morning shift has considerably more attendance records than the Evening shift. This suggests that most of the attendance records in the dataset are associated with the Morning shift. The comparison can also help management evaluate attendance patterns across different working shifts.

---

#### 4. Overall Attendance Status

<img width="752" height="452" alt="Overall Attendance Status" src="https://github.com/user-attachments/assets/e92c56e7-7b4d-4ac0-8386-5e9f492aef3b" />

**Interpretation:**
The overall attendance analysis shows that **Present is the most common attendance status**, indicating that the majority of recorded attendance entries represent employees who were present. **Late** is the next significant category, followed by Remote and Absent. This suggests that punctuality is a more noticeable attendance issue than complete absence in the dataset.




### Dashboard

An interactive **Employee Attendance Dashboard** was created to provide a visual overview of the attendance data.

The dashboard helps users quickly understand employee attendance patterns and identify important trends.

---

## 🔎 Key Findings

The analysis revealed several important observations from the employee attendance dataset:

* The original dataset contained **300 records**.
* After cleaning and removing problematic records, **261 valid records** remained.
* Several records contained missing or inconsistent information.
* Some employees had incorrect shift assignments compared with their actual check-in times.
* Department and shift values required standardization.
* Check-in and check-out times had inconsistent formats.
* Attendance status values required standardization before analysis.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* Excel Tables
* Data Cleaning
* Pivot Tables
* Pivot Charts
* Excel Dashboard
* Data Analysis

---

## 📂 Project Structure

```text
Employee-Attendance-Analysis/
│
├── Employee_Attendance_Analysis.xlsx
│
└── README.md
```

### Excel Workbook Sheets

```text
📄 row-data
    └── Original/raw attendance data

📄 cleaned-data
    └── Cleaned and standardized attendance data

📄 PivotTables
    └── Attendance analysis using Pivot Tables

📄 Dashboard
    └── Employee attendance dashboard

📄 finding
    └── Key findings from the analysis
```

---

## 📈 Analysis Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Standardization
   ↓
Clean Dataset
   ↓
Pivot Tables
   ↓
Dashboard
   ↓
Findings & Insights
```

---

## 🎯 Project Objectives

The main objectives of this project were to:

1. Clean and prepare employee attendance data.
2. Identify and handle missing and inconsistent values.
3. Standardize attendance-related information.
4. Analyze employee attendance patterns.
5. Build Pivot Tables for summarized analysis.
6. Create an Excel dashboard for visualization.
7. Extract meaningful findings from the dataset.

---

## 👨‍💻 Author

**Abdinajib**

This project was created as part of a practical **Data Analysis using Excel** project.
