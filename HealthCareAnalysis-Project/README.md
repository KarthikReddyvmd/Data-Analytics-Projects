# Healthcare Claims Cost Analysis Dashboard

## Project Overview

This project analyzes healthcare insurance claims data to identify the primary drivers of healthcare spending. The objective is to provide actionable insights that help insurance executives understand where costs are concentrated and identify opportunities to improve profitability through better cost management and reimbursement strategies.

The analysis focuses on claim types, medical procedures (CPT codes), diagnosis categories (ICD codes), member-level spending, provider-level spending, and reimbursement patterns.


## Business Problem

A health insurance company is experiencing increasing healthcare expenditures and wants to understand:

* Which claim types generate the highest costs?
* Which procedures and diagnoses drive healthcare spending?
* Which members account for the largest share of claim expenses?
* How do billed amounts compare to paid amounts?
* Which providers receive the highest reimbursements?

The goal is to identify key cost drivers and support data-driven decision-making.


## Dataset Description

### Members Dataset

Contains member demographic and enrollment information.

**Key Fields**

* Member ID
* Age
* Gender
* Plan Type
* Enrollment Dates

### Claims Dataset

Contains healthcare claim transactions.

**Key Fields**

* Claim ID
* Member ID
* Claim Type
* Provider ID
* CPT Code
* ICD Code
* Billed Amount
* Paid Amount


## Tools Used

* Microsoft Excel
* Power BI
* DAX (Data Analysis Expressions)


## Data Preparation

The following steps were performed before analysis:

1. Imported claims and member datasets into Power BI.
2. Created relationships between members and claims using Member ID.
3. Validated data types and field consistency.
4. Created calculated measures for business analysis.


## Key Metrics

### Total Claims

Total number of healthcare claims submitted.

### Total Billed Amount

Total amount billed by healthcare providers.

### Total Paid Amount

Total amount reimbursed by the insurance company.

### Paid Ratio

```text
Paid Ratio = Total Paid Amount / Total Billed Amount
```

Measures the percentage of billed charges that were reimbursed.

### Average Paid per Claim

```text
Average Paid per Claim = Total Paid Amount / Number of Claims
```

Used to identify expensive medical procedures.


## Dashboard Components

### Executive Overview

* Total Claims
* Total Billed Amount
* Total Paid Amount
* Paid Ratio

### Claim Type Analysis

* Total Paid by Claim Type
* Total Claims by Claim Type

### CPT Analysis

* Top CPT Codes by Total Paid Amount
* Most Expensive Procedures by Average Paid per Claim

### ICD Analysis

* Top ICD Diagnosis Codes by Total Paid Amount

### Member Analysis

* Top High-Cost Members
* Member-Level Spending Analysis
* Claim Type Contribution by Member

### Provider Analysis

* Provider Reimbursements
* Provider Paid Ratios

### Financial Analysis

* Billed vs Paid Amount Comparison


## Key Findings

* Inpatient claims account for the majority of healthcare spending and represent the largest cost driver.
* The insurance company reimbursed approximately 75% of billed charges.
* Emergency services are the second-largest spending category after inpatient care.
* A small number of members contribute a significant share of total healthcare expenditures.
* Healthcare spending is concentrated among a limited number of providers.
* Certain CPT procedures and ICD diagnosis codes generate a substantial portion of claim costs.
* Pharmacy and laboratory claims contribute relatively little to overall spending compared to inpatient and emergency services.


## Business Impact

The analysis helps identify areas where healthcare costs can be better controlled through:

* Monitoring high-cost inpatient services
* Managing high-risk members
* Reviewing expensive procedures
* Evaluating provider reimbursement patterns
* Improving cost-containment strategies

These insights support better financial planning and operational decision-making for healthcare insurers.


## Dashboard Preview

The dashboard provides an interactive view of healthcare spending patterns, allowing users to explore costs by claim type, procedure, diagnosis, member, and provider.


## Project Outcome

This project successfully identifies the primary drivers of healthcare spending and provides a clear view of reimbursement trends. The findings can be used to improve cost management, optimize provider contracts, and enhance overall profitability for the insurance organization.


## Author

**Karthik Reddy Vankamaddi**

B.Tech Computer Science and Engineering
Data Analytics & Business Intelligence Enthusiast
Power BI | Excel | SQL | Data Visualization

[![RepoRanker](https://reporanker.com/badge/KarthikReddyvmd/Data-Analytics-Projects)](https://reporanker.com/repos/KarthikReddyvmd/Data-Analytics-Projects)
