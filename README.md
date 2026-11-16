# Kenya Diabetes Burden & Epidemiological Insights (2024–2050)

## Project Overview

Diabetes is an important public health challenge with implications for healthcare systems, prevention programmes and long-term resource planning.

This project uses data from the International Diabetes Federation (IDF) Diabetes Atlas, 11th edition (2025), to examine Kenya's diabetes burden, diagnostic gaps, pre-diabetes indicators, diabetes-related expenditure and projected trends up to 2050.

The project demonstrates how healthcare data can be transformed into meaningful epidemiological insights through data preparation, analytical modelling and interactive visualisation using Microsoft Power BI.

## Project Objectives

- Examine the estimated diabetes burden in Kenya in 2024.
- Assess the proportion of diabetes cases that remain undiagnosed.
- Explore impaired fasting glucose (IFG) and impaired glucose tolerance (IGT) estimates.
- Examine diabetes-related mortality and expenditure indicators.
- Analyse historical estimates and projected diabetes growth through 2050.
- Communicate findings through an interactive Power BI dashboard.

## Data Source

**International Diabetes Federation (IDF) Diabetes Atlas, 11th edition (2025)**

Source: https://diabetesatlas.org/

Geographical focus: Kenya.

Main population focus: Adults aged 20–79 years, unless otherwise specified by an individual indicator.

The original and cleaned datasets are not included in this public repository. Source data should be accessed through the official IDF platform and used in accordance with its terms.

## Tools and Technologies

- Microsoft Excel – Data review and preparation
- Power Query – Data cleaning and transformation
- Microsoft Power BI – Data modelling and visualisation
- DAX – Analytical measures and calculations
- GitHub – Project documentation and version control

## Methodology

The project followed these main stages:

1. Data acquisition and source review.
2. Data cleaning and transformation using Power Query.
3. Development of a dimensional data model.
4. Creation of DAX measures and calculated indicators.
5. Development of interactive dashboard visuals.
6. Interpretation of findings and preparation of project documentation.

## Key Findings

Selected findings from the analysis include:

| Indicator | 2024 estimate |
|---|---:|
| People with diabetes | 813,300 |
| Undiagnosed diabetes | 435,700 |
| Undiagnosed share | 53.6% |
| Diagnosed diabetes (project-derived) | 377,600 |
| Age-standardised diabetes prevalence | 3.1% |
| Deaths attributable to diabetes | 9,377 |
| Impaired fasting glucose (IFG) | 1,032,200 |
| Impaired glucose tolerance (IGT) | 3,766,500 |

The IDF projection indicates that the number of adults with diabetes could reach approximately 1.8 million by 2050.

## Project Deliverables

- **Power BI Dashboard:** Interactive analysis of diabetes burden and epidemiological indicators.
- **Technical Project Report:** Detailed documentation of the data preparation, analytical approach, findings and limitations.
- **Project Presentation:** Summary of the project findings and implications.
- **Data Dictionary and DAX Reference:** Indicator definitions, verification notes, calculations and DAX documentation.

## Repository Structure

```text
Kenya-Diabetes-Burden-Analysis/
│
├── 01_Raw_Data/
├── 02_Cleaned_Data/
├── 03_Data_Analysis/
├── 04_PowerBI_Dashboard/
├── 05_Reports/
└── 06_Documentation/
```

## Important Notes and Limitations

- The 2024 values are IDF estimates while 2050 values are projections.
- Diagnosed diabetes and selected proportions are project-derived calculations.
- The calculated IGT share is not an IDF-published prevalence estimate.
- The original and cleaned datasets have been excluded from this public repository.
- Indicator definitions, population scope and units should be considered when interpreting results.
- Findings should be interpreted within the limitations of the source data and its estimation methodology.

## Conclusion

This project demonstrates the application of data analytics to public health challenges. By combining epidemiological indicators, data modelling and visual storytelling, it highlights the importance of data-driven decision-making in diabetes prevention, early detection and healthcare planning in Kenya.

**Developed as a healthcare data analytics portfolio project.**
