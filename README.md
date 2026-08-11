# Healthcare Analytics Dashboard (Excel)

## Overview
This project analyzes healthcare data using Microsoft Excel and presents key insights through an interactive dashboard. The dashboard includes KPI cards, charts, and slicers that allow users to explore healthcare charges and patient health metrics.

## Tools Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Excel Functions (IF, DATEDIF, CONCATENATE, VLOOKUP, COUNTIF, AVERAGE)

## Data Cleaning
- Replaced missing values in Month, Year, Smoker, Hospital Tier, City Tier, and State ID columns.
- Standardized inconsistent text values (Yes/No).
- Formatted Charges as currency.
- Replaced missing Number of Major Surgeries values with 0.

## Data Transformation
- Split Name into Title, First Name, and Last Name.
- Created **Weight Status** from BMI values.
- Created **Diabetes Status** from HBA1C values.
- Combined Year, Month, and Date into **Date of Birth**.
- Calculated **Age** using the DATEDIF function.
- Merged datasets using **VLOOKUP**.

## Visualizations
- **KPI Cards:** Total Patients, Average Charges, Average HBA1C, Total Major Surgeries
- **Pie Chart:** Cancer History Distribution
- **Column Chart:** Average Healthcare Charges by Weight Status and Diabetes Status
- **Scatter Plot:** Age vs HBA1C
- **Scatter Plot:** Age vs Charges

## Interactive Features
- **Weight Status slicer**
- **Diabetes Status slicer**

These slicers filter all connected charts and KPIs simultaneously for interactive analysis.

## Dashboard Highlights
- Total Patients: **2,335**
- Average Charges: **₹13,529.92**
- Average HBA1C: **6.58**
- Total Major Surgeries: **1,579**

## Outcome
The dashboard provides a clear view of patient health conditions, healthcare costs, and risk indicators, enabling quick comparison across weight categories and diabetes status.
