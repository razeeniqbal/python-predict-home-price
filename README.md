# Data Cleaning using Python for Analysis

*Scope of the Project*

The project aims to clean and prepare data for analysis using Python. The primary objective is to improve the quality of the dataset by rectifying errors, inconsistencies, and inaccuracies, thereby ensuring that the data is suitable for accurate and meaningful analysis. 

Key tasks include:
- Identifying and correcting errors and inconsistencies in the dataset.
- Removing duplicate entries.
- Handling missing values.
- Standardizing data formats.
- Ensuring overall data integrity and accuracy.

*Software Used / Process / Methodology*

Software Used:
- Python

Libraries Used:
- pandas: For data manipulation and cleaning.
- zipfile: For handling zipped data files.
- kaggle: For accessing and downloading datasets from Kaggle.


*Process and Methodology:*


1. Initial Data Review:
- Load the dataset into a pandas DataFrame.
- Perform an initial review to identify obvious errors and inconsistencies.


2. Data Cleaning Steps:
- Loading Data:
  - Use zipfile to extract data from compressed files if necessary.
  - Utilize the kaggle library to download datasets directly from Kaggle.
- Inspecting Data:
  - Use functions like df.head(), df.info(), and df.describe() to understand the structure and summary statistics of the data.
- Removing Duplicates:
  - Use df.drop_duplicates() to eliminate redundant records.
- Data Type Conversion:
  - Convert data types as necessary using astype() to ensure consistency.
- Data Standardization:
  - Standardize data formats (e.g., dates, strings) using pandas functions like pd.to_datetime() and string manipulation methods.
- Data Validation:
  - Implement validation checks to ensure data consistency and integrity using custom functions or conditions.


3. Documentation:
- Keep detailed records of all steps and transformations applied during the data cleaning process.
- Document any assumptions or decisions made while handling data inconsistencies or missing values.

You can refer the full codes here [(see notebook)](https://github.com/razeeniqbal/python-london-bike/blob/main/london_bikes_code.ipynb). 

*End Result / Conclusion*

End Result:

- A cleaned, structured, and well-organized dataset free from errors, duplicates, and inconsistencies.
- Enhanced data quality that facilitates accurate and reliable analysis.
- A dataset that adheres to standardized formats and validation rules, ensuring better data integrity.

Conclusion:
The data cleaning process using Python and its powerful libraries, such as pandas, significantly improved the quality of the dataset. By systematically addressing errors, inconsistencies, and missing values, the dataset was transformed from a raw state to a refined state, ready for in-depth analysis. This project highlights the critical role of data cleaning in the data analysis workflow, ensuring that subsequent analyses and insights are based on accurate and trustworthy data.

*Before*

![plot](https://github.com/razeeniqbal/python-london-bike/blob/main/london_merged.png)

*After*

![plot](https://github.com/razeeniqbal/python-london-bike/blob/main/london_bikes_final.png)
