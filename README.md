
## Travel, Food and Beverages: Adverse Event Reporting in Food and Cosmetics Industry.
![Food-Cosmetics ](https://github.com/shaikh111-Z/PowerBi/assets/83855661/2395a799-2177-4f84-b123-0a977ff966a1)


# Problem Statement
The FDA relies on the CAERS database to manage adverse event and product complaint reports in the food, dietary supplements, and cosmetics industries. Despite its wealth of data spanning from 2004 to the second quarter of 2017, there's a need to extract actionable insights from this dataset. The challenge lies in effectively analyzing the detailed records to identify patterns, trends, and potential risks associated with various products. By leveraging this information, regulatory policies can be better informed to enhance product safety surveillance and improve public health outcomes.

# Objective
The primary objective of this analysis is to gain insights into adverse events associated with food, dietary supplements, and cosmetics reported to the FDA. The analysis aims to identify patterns and trends in adverse events, including product categories, demographic characteristics, symptoms, and outcomes.

# Overview
The CAERS database is maintained by the FDA and contains reports of adverse events and product complaints related to foods, dietary supplements, and cosmetics. The dataset spans from 2004 to the second quarter of 2017 and includes detailed records coded using MedDRA terminology.
This Power BI project aims to streamline the reporting process of adverse events in the food and cosmetics industry. Adverse events, such as allergic reactions or product defects, require careful monitoring and reporting to ensure consumer safety and regulatory compliance. This project provides a user-friendly interface to track and analyze adverse events efficiently.
This repository contains a comprehensive analysis of adverse event reporting in the food, dietary supplements, and cosmetics industries using the CFSAN Adverse Event Reporting System (CAERS) dataset. The analysis is conducted in two parts: data cleaning, modeling, and DAX in Power BI, followed by dashboard building.


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
- Data Importing and Preliminary Analysis: Importing the dataset into Power BI and identify inconsistencies or data quality issues.
- Handling Missing Values: Investigated and addressed missing values using appropriate strategies.
- Data Type Standardization: Ensured correct identification and conversion of data types.
- Product Role Categorization: Categorization of  products based on their roles and analyzed their distribution.
- FDA Industry Analysis: Group data by FDA industry names and analyzed the frequency of reports.
- Age Group Analysis: Analyzed the distribution of adverse events across age groups.
- Gender-Based Analysis: Examined differences in adverse event reporting between genders.
- Adverse Event Start Date Analysis: Identify trends or patterns in the distribution of event start dates.
- Outcome Categorization: Categorized outcomes and analyzed their distribution.
- Symptom Frequency Analysis: Analyzed the most frequently reported symptoms.
- Industry and Outcome Relationship: Established the relationship between industry and reported outcomes.
- DAX for Advanced Age Analysis: Calculated average, median, and mode of ages at which adverse events occur.
- Product Name Analysis: Identified commonly reported products using text analysis.
- Symptom Severity Index: Created a severity index for symptoms.
- Predictive Modeling for Adverse Event Risk: Created a predictive model estimating the risk of adverse events.

# Dashboard Building
- Adverse Event Reporting Dashboard: Developed a comprehensive dashboard showcasing key metrics and providing interactive filters.
- Dashboard Design and Accessibility: Ensured the dashboard is visually appealing, easy to navigate, and accessible.
- Time-Based Reporting Trends: Visualize trends in adverse event reporting over time.
- Demographic Analysis: Analyzing demographic data.
- Key Insights and Data Storytelling: Summarized key insights and trends using visual storytelling techniques.

# Key Insights 
- **Product Role Distribution**: Understanding the distribution of product roles (suspect vs. concomitant) can provide insights into which products are more commonly associated with adverse events. This insight could guide regulatory focus and industry interventions.
- **FDA Industry Analysis**: Analyzing the frequency of reports across different FDA industry categories can highlight sectors of the food and cosmetics industries that are more prone to adverse events. This insight could inform targeted regulatory measures or industry standards.
- **Demographic Patterns**: Identifying demographic patterns such as age and gender distributions among individuals experiencing adverse events can help tailor risk communication strategies and product safety guidelines to specific demographic groups.
- **Outcome Analysis**: Categorizing and analyzing adverse event outcomes can reveal the severity and impact of reported incidents. Identifying common outcomes can prioritize interventions to mitigate serious adverse events.
- **Symptom Frequency and Severity**: Identifying the most frequently reported symptoms and their severity can highlight specific health risks associated with certain products or ingredients. This insight could guide product formulation and labeling requirements.
- **Industry and Outcome Relationships**: Exploring the relationship between industry sectors and reported outcomes can highlight sectors with higher incidence of serious adverse events. This insight could drive industry-specific risk management strategies and regulatory oversight.
- **Predictive Modeling for Adverse Event Risk**: Developing predictive models for adverse event risk can help identify products or demographic groups which are at higher risk.

# Technical Summary 
- The project involves analyzing the CAERS dataset, which contains adverse event reports related to foods, dietary supplements, and cosmetics. The analysis is conducted using Power BI, focusing on data cleaning, modeling, and visualization.
- Data is imported into Power BI for preliminary analysis, addressing missing values and standardizing data types. Product roles are categorized, and FDA industry codes are analyzed to understand reporting patterns. Age, gender, and temporal trends in adverse events are examined, along with outcomes and symptom frequencies.
- Advanced DAX calculations are used for age analysis, report frequency calculation, and predictive modeling for adverse event risk. Insights include product role distributions, demographic patterns,outcome analysis, symptom severity, and industry relationships.
- The project culminates in the development of an interactive dashboard showcasing key metrics and insights, aiding in regulatory decision-making and public health improvement efforts.

# Conclusion
In conclusion, this project provides valuable insights into adverse event reporting in the food and cosmetics industries through analysis of the CAERS dataset using Power BI. By identifying patterns and trends in adverse events, such as product roles, demographic distributions and outcome analysis, we enhance product safety surveillance and inform regulatory policies. The interactive dashboard developed as part of this project serves as a powerful tool for stakeholders to make informed decisions, ultimately contributing to improving public health outcomes and ensuring consumer safety and survellence and promoting public health outcomes in the food and cosmetics sectors.

Below are glimpses of the dashboard highlighting key metrics and findings.

![1](https://github.com/shaikh111-Z/PowerBi/assets/83855661/af90789c-fb70-4c08-a0f0-aa7e3866be4b)


![2](https://github.com/shaikh111-Z/PowerBi/assets/83855661/26246387-e4c7-41de-935c-118830161a2d)


![3](https://github.com/shaikh111-Z/PowerBi/assets/83855661/3c872874-774f-418f-ab4a-27149c8e97ee)


![4](https://github.com/shaikh111-Z/PowerBi/assets/83855661/ef1a3f36-3032-44cf-85e3-cb355913199d)

