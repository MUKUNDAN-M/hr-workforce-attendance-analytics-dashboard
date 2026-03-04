# HR Workforce Attendance Analytics Dashboard

## Project Overview
This project analyzes employee attendance data to generate actionable HR insights using Power BI. The dataset contains employee attendance records including presence, work-from-home (WFH), and sick leave information across multiple months. 

The objective of this project is to transform raw attendance data into meaningful insights that help HR teams understand workforce behavior and support data-driven decision-making.

---

## Problem Statement
HR teams often need visibility into workforce attendance patterns to answer key questions such as:
- What is the overall employee presence rate?
- How frequently do employees work from home?
- Are there patterns in sick leave trends?
- Which days have higher office attendance?

This dashboard provides an analytical solution to monitor attendance trends and improve workforce planning.

---

## Dataset
The dataset contains employee attendance records for three months.

Attendance codes used in the dataset include:
- **WO** – Work from Office
- **WFH** – Work from Home
- **SL** – Sick Leave
- **PL** – Paid Leave

Employee names and IDs were randomized to maintain confidentiality.

---

## Data Preparation
Data preparation and transformation were performed using **Power Query** in Power BI.

Key steps included:
- Importing multi-sheet Excel data into Power BI
- Cleaning inconsistent data formats
- Converting wide-format data into normalized format using **Unpivot Columns**
- Consolidating multiple monthly sheets into a single dataset
- Creating reusable transformation steps for scalability

Final dataset structure:
- Employee Code
- Employee Name
- Date
- Attendance Status

---

## Data Modeling & Metrics
Key HR metrics were created using **DAX (Data Analysis Expressions)**.

Important measures include:

**Presence %**

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

