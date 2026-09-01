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

<img width="765" height="452" alt="image" src="https://github.com/user-attachments/assets/c6156aa4-a821-4dd8-b0d8-d693fde60f1f" />


**Interpretation:**
The chart shows the distribution of attendance statuses across the six departments. IT has the highest number of attendance records (76), including 49 Present, 13 Late, 7 Absent, and 7 Remote records. HR has the lowest number of records (20). Overall, Present is the dominant attendance status across all departments, while IT and Sales have relatively higher numbers of Absent and Late records.

---

#### 2. Employees by Department

<img width="765" height="452" alt="image" src="https://github.com/user-attachments/assets/f947e697-6f56-4293-ba9f-b2853490b6a9" />


**Interpretation:**
The chart shows the number of employee attendance records by department. IT has the highest number with 76 records, followed by Operations with 51 and Finance with 45. Sales has 39 records, Administration has 30, and HR has the lowest with 20 records. This indicates that IT represents the largest department in the analyzed dataset.

---

#### 3. Attendance by Shift

<img width="764" height="452" alt="image" src="https://github.com/user-attachments/assets/405a0243-6838-4c03-bcc3-fbeb8aba9feb" />


**Interpretation:**
The chart compares attendance status between the Morning and Evening shifts. The Morning shift has 173 records, compared with 88 records for the Evening shift. The Morning shift also has the highest number of Present records (110) and Late records (29), while the Evening shift has 58 Present and 16 Late records. This shows that the majority of attendance records belong to the Morning shift.

---

#### 4. Overall Attendance Status

<img width="765" height="452" alt="image" src="https://github.com/user-attachments/assets/0553b128-ffc2-439a-9ee3-703a6f41744e" />


**Interpretation:**
The overall attendance chart summarizes the attendance status of all 261 records. Present is the largest category with 168 records (64.4%), followed by Late with 45 records (17.2%), Remote with 27 records (10.3%), and Absent with 21 records (8.0%). This indicates that the majority of attendance records represent employees who were present, although late attendance is significantly higher than absence.




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
