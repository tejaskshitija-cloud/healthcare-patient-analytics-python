# Hospital Length-of-Stay Analytics

## 1. Project Overview
This project analyses a synthetic hospital encounter dataset to explore length of stay (LOS), pain scores, and department-level patterns. The aim is to demonstrate healthcare data quality validation, KPI reporting, and exploratory data analysis.

**Important:** The dataset is synthetic and does not represent actual patients or hospital outcomes.

## 2. Business Problem
Healthcare teams need clear, reliable reports to monitor patient stays and identify patterns that may deserve further review. This project demonstrates how healthcare data can be converted into understandable performance indicators.

## 3. Dataset
- Total encounters: 5,000
- Unique patients: 2,603
- Departments: 5
- Diagnoses: 8
- Long stay definition: more than 14 days

## 4. Data Quality Checks
The analysis checked for:
- Missing values
- Duplicate records and encounter IDs
- Length-of-stay consistency
- Invalid dates and negative length of stay
- Age and pain scores outside expected ranges

The reported validation checks found no issues in these categories.

## 5. Key Performance Indicators
- Average length of stay: 6.61 days
- Average pain score: 4.75 out of 10
- Long-stay encounters: 180
- Long-stay rate: 3.60%

## 6. Key Findings
- Neurology had the highest long-stay rate in this dataset: 13.38%.
- Orthopedics had 98 long-stay encounters, compared with 82 in Neurology.
- Orthopedics had the highest average pain score: 6.50 out of 10.
- Neurology had the highest average length of stay: 9.17 days.
- No long-stay encounters appeared in the other three departments in this synthetic dataset.

These are descriptive findings from synthetic data, not evidence of real-world clinical performance or cause and effect.

## 7. Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab
- Excel
- Power BI (for related dashboard work)

## 8. Project Outputs
- Data quality validation
- Hospital KPI summary
- Department-level analysis
- Visualisations of long-stay rates, average length of stay, and average pain scores
- Excel results workbook

## 9. Limitations
The dataset is synthetic. The findings cannot be generalised to real hospitals. Further work would require appropriate real-world data, clinical context, and validation before operational use.

## 10. Future Improvements
- Develop an interactive Power BI dashboard.
- Add time-based trend analysis.
- Investigate relevant factors associated with longer stays.
- Validate analytical methods using suitable real-world data where access and permissions allow.

## Skills Demonstrated
Healthcare analytics, data quality assessment, KPI development, data aggregation, exploratory data analysis, visualisation, and healthcare reporting.
