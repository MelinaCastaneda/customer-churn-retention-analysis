# Customer Churn & Retention Analysis

## Project Overview

This project analyzes customer churn patterns in a telecommunications dataset to identify customer and account characteristics associated with higher churn rates.

Using Excel, I performed data quality checks, created PivotTable analyses, calculated segment level churn rates, and developed visualizations to communicate findings and potential areas for further business investigation.

## Business Question

What customer and account characteristics are associated with customer churn?

## Dataset

- **Source:** IBM Telco Customer Churn sample dataset
- **Size:** Approximately 7,000 customer records
- **Industry:** Telecommunications
- **Outcome analyzed:** Customer churn (Yes/No)

  ## Tools

  - Microsoft Excel
  - PivotTables
  - Excel formulas
  - Data cleaning and validation
  - Data visualization
  - Descriptive analysis
 
  ## Methodology

1. Reviewed the dataset for missing values, duplicate customer IDs, data-type issues, and inconsistent categorical values.
2. Preserved the original data and conducted the analysis using a separate working copy.
3. Grouped customer tenure and monthly charges into categories for comparison.
4. Calculated churn rates within customer segments using PivotTables and percentage-of-row totals.
5. Created charts and summarized findings for a business-focused audience.

The analysis focuses on observed relationships and does not establish causation.

## Key Findings

- **Contract type:** Month to month customers had an observed churn rate of 42.71%, compared with 2.83% for two year contract customers.
- **Customer tenure:** Customers with 0–12 months of tenure had the highest observed churn rate at 47.44%, compared with 9.51% among customers with 49+ months of tenure.
- **Payment method:** Customers using electronic checks had an observed churn rate of 45.29%, substantially higher than customers using other payment methods.
- **Internet service:** Fiber optic customers had an observed churn rate of 41.89%, compared with 18.96% among DSL customers.
- **Monthly charges:** The upper-middle monthly-charge group had the highest observed churn rate at 37.51%. The lowest-charge group had a churn rate of 11.24%.

## Business Implications


## Business Implications

The findings suggest several areas for further investigation by customer success and retention teams:

1. **Contract strategy:** Investigate retention opportunities for month-to-month customers and evaluate whether contract flexibility or incentives influence retention.
2. **Customer onboarding:** Review the early customer experience to identify potential friction points during the first year.
3. **Payment experience:** Investigate whether electronic-check customers experience different billing issues, payment failures, or customer-service needs.
4. **Fiber optic experience:** Examine service quality, pricing, customer satisfaction, and support interactions among fiber optic customers.
5. **Pricing and perceived value:** Evaluate whether higher monthly charges correspond with customer concerns about affordability or perceived value.

These are recommendations for further investigation, not confirmed explanations for churn.

## Limitations

This analysis identifies associations within the dataset but does not establish causation. The dataset does not contain information such as cancellation reasons, customer satisfaction, competitor pricing, payment failures, billing disputes, service outages or customer support interactions. 

These additional variables would help explain why customers churn and support more targeted retention strategies.

## Project Files

- **[Excel Workbook](excel/customer_churn_retention_analysis.xlsx)** -Complete analysis, including the executive summary, methodology, PivotTables, charts, and findings.
- **[Dataset](data/Telco-Customer-Churn.csv)** - Original Telco Customer Churn dataset used for the analysis.
- **[Visualizations](images/)** - Screenshots of the executive summary, methodology, and individual analyses.
