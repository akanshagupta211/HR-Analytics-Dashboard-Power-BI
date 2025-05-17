# HR-Analytics-Dashboard-Power-BI

## 📊 Overview
This repository features an interactive HR Analytics Dashboard developed using Power BI. The dashboard offers valuable insights and visualizations derived from an HR dataset, aiming to help organizations manage their workforce more effectively and align with business goals. The primary objective is to monitor key HR metrics and identify factors contributing to employee attrition. Multiple reports have been created to analyze various dimensions such as age, salary, job role, and education—empowering organizations to take informed actions for improving employee retention.

---

## 📁 Dataset
The dataset used includes information on:
- Employee demographics (Age, Gender, Education)
- Employment details (Department, Job Role, Salary, Years at Company)
- Performance metrics (Job Satisfaction, Attrition Status)

These fields are used to build insightful visualizations that reveal patterns of attrition and satisfaction.

---

## 🧰 Tools Used
- **Power BI** – for dashboard creation
- **Power Query** – for data cleaning and transformation
- **DAX** – for calculated measures, KPIs, and logic

---

## 🔍 Data Cleaning & Transformation (Power Query)
 - Connected the employee dataset using Excel and Power Query. 
 - Performed data transformation and cleaning steps such as: 
    - Removing duplicates 
    - Renaming columns 
    - Changing data types 
 - Created a copy template for a sheet and applied uniform transformations across all sheets. 
 - Introduced a parameter to filter data based on specific conditions. 
 - Encapsulated all transformation steps into a reusable function for future datasets. 
 - Loaded the cleaned and structured data into Power BI for analysis.

---


## 📊 Dashboard Visualizations

The dashboard includes the following components:

### ✅ KPI Cards:
- Count of Employees: 1470  
- Total Attrition: 237  
- Attrition Rate: 16.1%  
- Avg Age: 37  
- Avg Salary: 6.5K  
- Avg Years at Company: 7.0  

### 📈 Charts & Insights:
- **Attrition by Gender:** Bar chart (77% higher in males)
- **Attrition by Age:** Column chart showing highest in 26–35 age group
- **Attrition by Education:** Donut chart (Life Sciences 38%, Medical 27%)
- **Attrition by Salary Slab:** Bar chart – highest in ≤5K group
- **Attrition by Years at Company:** Area chart – over 50% leave within 5 years
- **Attrition by Job Role:** Bar chart – top attrition in Lab Technician & Sales Executive
- **Matrix View:** Job Role vs. Satisfaction Level breakdown

### 🎯 Filters:
- Department filter: Human Resources, Research & Development, Sales

---

## 🖼️ Screenshot

![HR Analytics Dashboard Screenshot](screenshots/Screenshot%202025-05-16%20133702.png)

> Screenshot is stored in `screenshots/` folder for reference.

---

## 🚀 How to Use
1. Download the PBIX file from this repo.
2. Open in Power BI Desktop.
3. Interact with the filters, slicers, and visualizations to explore the insights.

---

## 📌 Conclusion
This HR Dashboard enables organizations to:
- Identify key drivers of employee attrition
- Monitor job satisfaction across roles
- Segment employees by salary, age, and tenure for better engagement strategies

It helps HR teams make data-driven decisions and enhance employee retention programs.

---

## 📫 Contact
For questions, suggestions, or collaboration, feel free to connect!

---

