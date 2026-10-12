# OASIS INFOBYTE - Data Analytics Internship

## Task 3: Data Cleaning Using Python

### Project Overview
This project focuses on cleaning and preparing the Titanic dataset using Python, Pandas, and NumPy. The objective is to improve data quality by handling missing values, checking duplicates, standardizing categorical data, correcting data types, and detecting outliers.

### Dataset
- **Dataset:** Titanic Dataset
- **Source:** Kaggle Titanic Competition
- **Original Rows:** 891
- **Original Columns:** 12

### Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

### Data Cleaning Steps
1. Loaded and inspected the dataset.
2. Identified missing values and calculated missing-value percentages.
3. Filled missing Age values using the median.
4. Filled missing Embarked values using the mode.
5. Investigated missing Cabin values.
6. Checked for duplicate records and removed duplicates if present.
7. Standardized categorical values.
8. Checked and corrected data types.
9. Checked for invalid values.
10. Detected potential outliers using the Interquartile Range (IQR) method.
11. Generated a before-and-after data quality report.
12. Exported the cleaned dataset as a CSV file.

### Missing Value Treatment

| Column | Method |
|---|---|
| Age | Median imputation |
| Embarked | Mode imputation |
| Cabin | Missing values retained for further investigation |

### Outlier Detection
The IQR method was used to identify potential outliers in numerical columns. The flagged observations were retained because extreme values may represent genuine passenger data.

### Project Files
- `OIBSIP_Task3_Data_Cleaning.ipynb` — Notebook containing the analysis and cleaning code.
- `cleaned_titanic.csv` — Cleaned dataset.
- `README.md` — Project documentation.

### Conclusion
This project demonstrates a structured data-cleaning workflow using Python. The cleaned dataset and data quality report can be used for further exploratory data analysis.

### Internship
OASIS INFOBYTE Data Analytics Internship
