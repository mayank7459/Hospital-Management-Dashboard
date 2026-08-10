# Hospital Management Dashboard

## About the Project

I created this project to understand how hospital data can be analyzed using SQL and Power BI.

The main goal was to get a clear view of hospital visits, patients, doctors, revenue, departments and admission types in one dashboard.

I worked with the data in SQL first and then used Power BI to build the final interactive dashboard.

## Tools Used

- SQL (PostgreSQL)
- Power BI
- DAX
- CSV files

## What I Analyzed

In SQL, I worked on basic hospital metrics and different types of analysis such as:

- Total visits
- Total patients
- Total doctors
- Total revenue
- Average revenue per visit
- Average revenue per patient
- Average stay days
- Average patients per doctor
- Revenue by department
- Revenue by payment mode
- Visits by admission type
- Average stay days by admission type

I also used SQL results to cross-check some of the numbers shown in Power BI.

## Power BI Dashboard

The dashboard contains 8 main KPIs:

- Total Revenue
- Total Patients
- Total Visits
- Total Doctors
- Average Revenue per Visit
- Average Stay Days
- Average Revenue per Patient
- Average Patients per Doctor

### Charts

- Monthly Revenue Trend
- Revenue by Department
- Revenue by Payment Mode
- Visits by Admission Type
- Average Stay Days by Admission Type

### Filters

I added two slicers to make the dashboard interactive:

- Year
- Department

Selecting a year or department updates the KPIs and charts accordingly.

## SQL

The SQL queries used for the project are available in:

`SQL/Hospital_Management_SQL.sql`

## Dataset

The project uses CSV files containing hospital-related data such as:

- Visits
- Patients
- Doctors
- Departments

The tables were connected in Power BI using their respective IDs.

## What I Learned

While working on this project, I practiced:

- SQL joins
- GROUP BY and HAVING
- Aggregate functions
- CASE statements
- CTEs
- Window functions
- Data relationships in Power BI
- DAX measures
- Power BI visuals
- Slicers and dashboard formatting

## Project File

The main Power BI dashboard is:

`Hospital_Management_Dashboard.pbix`