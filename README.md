# Bank Loan Report Project

## Problem Statement
The objective of this project is to monitor and assess our bank's lending activities and performance through a comprehensive Bank Loan Report. This report will provide insights into key loan-related metrics and their changes over time, helping us make data-driven decisions, track our loan portfolio's health, and identify trends to inform our lending strategies.

## Dashboards Overview

### Dashboard 1: Summary
This dashboard provides a high-level overview of our bank's lending metrics, including:

- **Total Loan Applications**: Calculate the total number of loan applications received during a specified period, including Month-to-Date (MTD) Loan Applications and Month-over-Month (MoM) changes.
- **Total Funded Amount**: Track the total amount of funds disbursed as loans, with MTD and MoM analysis.
- **Total Amount Received**: Monitor the total amount received from borrowers, with MTD and MoM analysis.
- **Average Interest Rate**: Calculate the average interest rate across all loans, with MTD and MoM variations.
- **Average Debt-to-Income Ratio (DTI)**: Evaluate the average DTI for borrowers, with MTD and MoM fluctuations.

### Good Loan vs. Bad Loan KPIs
Distinguish between 'Good Loans' and 'Bad Loans' based on specific loan status criteria:

- **Good Loans**:
  - Good Loan Application Percentage
  - Good Loan Applications
  - Good Loan Funded Amount
  - Good Loan Total Received Amount

- **Bad Loans**:
  - Bad Loan Application Percentage
  - Bad Loan Applications
  - Bad Loan Funded Amount
  - Bad Loan Total Received Amount

### Dashboard 1: Loan Status Grid View
Gain a comprehensive overview of lending operations and monitor the performance of loans categorized by 'Loan Status', including metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'MTD Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI).'

![Screenshot 2024-06-18 010104](https://github.com/Sankari0299/Bank-Loan-Project-----Tableau/assets/122591357/ae097928-df14-4e1c-80dd-7f878a5e3740)

### Dashboard 2: Overview
Visualize critical loan-related metrics and trends using various chart types:

1. **Monthly Trends by Issue Date (Line Chart)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: Identify seasonality and long-term trends in lending activities.

2. **Regional Analysis by State (Filled Map)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: Assess regional disparities in lending activities.

3. **Loan Term Analysis (Donut Chart)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: Understand the distribution of loans across various term lengths.

4. **Employee Length Analysis (Bar Chart)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: Assess the impact of employment history on loan applications.

5. **Loan Purpose Breakdown (Bar Chart)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: Understand the primary reasons borrowers seek financing.

6. **Home Ownership Analysis (Tree Map)**:
   - Metrics: 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received'
   - Objective: View how home ownership impacts loan applications and disbursements.

![Screenshot 2024-06-18 010118](https://github.com/Sankari0299/Bank-Loan-Project-----Tableau/assets/122591357/020cf9ed-5d5f-4ede-a4b2-9bd5e5643a6b)

### Dashboard 3: Details
The Details Dashboard provides a consolidated view of all essential loan data, offering a holistic snapshot of key loan-related metrics and data points for efficient access to critical information.

![Screenshot 2024-06-18 010132](https://github.com/Sankari0299/Bank-Loan-Project-----Tableau/assets/122591357/6ed88fc6-5acf-4a51-84ae-23dacdea92dd)

## Dependencies
- Microsoft SQL Server: Queries are written in Microsoft SQL Server.
- Tableau: Dashboards are built using Tableau for data visualization.

## Getting Started

### Prerequisites
- Microsoft SQL Server
- Tableau

## Installation and Setup
SQL Server Setup:
- Ensure you have Microsoft SQL Server installed and running.
- Execute the SQL scripts provided in the /sql directory to create and populate the database.

## Tableau Setup:
- Open the Tableau workbooks provided in the /tableau directory.
- Connect the workbooks to your SQL Server instance.

## Run the Project:
- Follow the instructions in the README files within the /sql and /tableau directories for detailed setup and usage guidelines.
---
Feel free to reach out if you have any questions or need further assistance. Happy analyzing!
