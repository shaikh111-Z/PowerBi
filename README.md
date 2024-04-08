# PowerBi
Travel Food and Beverages Industry - Adverse Event Reporting in Food and Cosmetics Industry

# Objective
The primary objective of this analysis is to gain insights into adverse events associated with food, dietary supplements, and cosmetics reported to the FDA. The analysis aims to identify patterns and trends in adverse events, including product categories, demographic characteristics, symptoms, and outcomes.

# Overview
This Power BI project aims to streamline the reporting process of adverse events in the food and cosmetics industry. Adverse events, such as allergic reactions or product defects, require careful monitoring and reporting to ensure consumer safety and regulatory compliance. This project provides a user-friendly interface to track and analyze adverse events efficiently.
This repository contains a comprehensive analysis of adverse event reporting in the food, dietary supplements, and cosmetics industries using the CFSAN Adverse Event Reporting System (CAERS) dataset. The analysis is conducted in two parts: data cleaning, modeling, and DAX in Power BI, followed by dashboard building.

# Background
The CAERS database is maintained by the FDA and contains reports of adverse events and product complaints related to foods, dietary supplements, and cosmetics. The dataset spans from 2004 to the second quarter of 2017 and includes detailed records coded using MedDRA terminology.

# Various Attributes
1. **RA_Report #**: A unique identifier for each adverse event report.
2. **RA_CAERS Created Date**: The date when the report was entered into the CAERS database.
3. **AEC_Event Start Date**: The date when the adverse event started.
4. **PRI_Product Role**: Indicates whether the product was a suspect or concomitant (present during the event but not necessarily the cause).
5. **PRI_Reported Brand/Product Name**: The name of the product reported to be associated with the adverse event.
6. **PRI_FDA Industry Code & Name**: Categorization of the product based on FDA industry codes and names, such as 'Bakery Prod/Dough/Mix/Icing', 'Ice Cream Prod', etc.
7. **CI_Age at Adverse Event**: Age of the individual experiencing the adverse event.
8. **CI_Age Unit**: Unit of measurement for age (e.g., years, months).
9. **CI_Gender**: Gender of the individual.
10. **AEC_One Row Outcomes**: Describes the outcomes of the event, such as hospitalization, ER visit, or non-serious injuries/illness.
11. **SYM_One Row Coded Symptoms**: Lists the symptoms reported in association with the adverse event.

# Part I : Data Cleaning, Data Preprocessing and DAX in Power Bi
- Data Importing and Preliminary Analysis: Import the dataset into Power BI and identify inconsistencies or data quality issues.
- Handling Missing Values: Investigate and address missing values using appropriate strategies.
- Data Type Standardization: Ensure correct identification and conversion of data types.
- Product Role Categorization: Categorize products based on their roles and analyze their distribution.
- FDA Industry Analysis: Group data by FDA industry names and analyze the frequency of reports.
- Age Group Analysis: Analyze the distribution of adverse events across age groups.
- Gender-Based Analysis: Examine differences in adverse event reporting between genders.
- Adverse Event Start Date Analysis: Identify trends or patterns in the distribution of event start dates.
- Outcome Categorization: Categorize outcomes and analyze their distribution.
- Symptom Frequency Analysis: Analyze the most frequently reported symptoms.
- Correlation between Age and Symptom Types: Investigate if there's a correlation between age and reported symptoms.
- Industry and Outcome Relationship: Examine the relationship between industry and reported outcomes.
- Time Series Analysis of Reports: Identify seasonal trends in report submissions.
- DAX for Advanced Age Analysis: Calculate average, median, and mode of ages at which adverse events occur.
- Product Name Analysis: Identify commonly reported products using text analysis.
- Geographical Distribution: Analyze the distribution of reports by region if applicable.
- Symptom Severity Index: Create a severity index for symptoms.
- Predictive Modeling for Adverse Event Risk: Create a predictive model estimating the risk of adverse events.

# Dashboard Building

