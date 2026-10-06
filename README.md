# Bank Customer Churn Analysis 

## Project Overview

This project analyzes customer churn data for a fictitious European bank to identify characteristics associated with customers leaving the bank. Using Microsoft Excel, I cleaned and validated the dataset, analyzed churn across customer segments with PivotTables, and built an interactive dashboard with dynamic KPIs and slicers.

The analysis focuses on identifying high-churn customer segments and translating the findings into actionable insights that could support customer retention strategies.

## Business Objective

The bank wants to better understand which customer segments are most likely to churn and where retention efforts may be most valuable.

This analysis aims to:

- Measure the bank's overall customer churn rate.
- Identify demographic and behavioral characteristics associated with higher churn.
- Compare churn across age groups, geographic markets, activity status, and number of products.
- Identify high-risk customer segments that could be prioritized for retention efforts.
- Build an interactive Excel dashboard that allows users to explore churn patterns by gender and geography.

## Data Dictionary

| Field | Description |
|---|---|
| `CustomerId` | A unique identifier for each customer |
| `Surname` | The customer's last name |
| `CreditScore` | A numerical value representing the customer's credit score |
| `Geography` | The country where the customer resides (France, Spain, or Germany) |
| `Gender` | The customer's gender (Male or Female) |
| `Age` | The customer's age |
| `Tenure` | The number of years the customer has been with the bank |
| `Balance` | The customer's account balance |
| `NumOfProducts` | The number of bank products the customer uses (e.g., savings account, credit card) |
| `HasCrCard` | Whether the customer has a credit card (1 = yes, 0 = no) |
| `IsActiveMember` | Whether the customer is an active member (1 = yes, 0 = no) |
| `EstimatedSalary` | The estimated salary of the customer |
| `Exited` | Whether the customer has churned (1 = yes, 0 = no) |

## Tools & Excel Skills

**Tool:** Microsoft Excel

**Skills demonstrated:**
- Data cleaning and validation
- Excel Tables and structured references
- PivotTables for customer segmentation
- Calculated churn rates using counts and percentages
- Grouping continuous variables such as age, credit score, balance, and salary
- `GETPIVOTDATA` for connecting PivotTable results to dashboard visuals
- Interactive slicers with Report Connections
- Dynamic KPI cards
- Clustered column charts
- Interactive dashboard design

## Analysis

The analysis explored the following questions:

- What is the bank's overall customer churn rate?
- How does churn vary across age groups?
- Do customers in different geographic markets have different churn rates?
- Does customer activity status relate to churn?
- Does the number of bank products a customer holds relate to churn?
- Are credit score, account balance, tenure, salary, or credit-card ownership associated with meaningful differences in churn?
- Which combinations of customer characteristics identify particularly high-churn segments?

