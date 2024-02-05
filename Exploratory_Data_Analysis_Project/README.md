# Exploratory Data Analysis Project: Student Mental Health

## Overview

This exploratory data analysis project focuses on understanding various aspects of student mental health based on a dataset. The dataset includes information about students' gender, age, course, year of study, CGPA, marital status, and responses to questions related to depression, anxiety, panic attacks, and seeking specialist treatment.

## Data Cleaning

In this project, a series of cleaning steps were applied to ensure the dataset's integrity and prepare it for analysis:

- **Handling Missing Values:** Null values were dropped from the dataset using `dropna()` to maintain data completeness.
- **Checking for Duplicates:** Duplicate entries were identified and removed using the `duplicated()` method.
- **Removing Unnecessary Column:** The column 'Timestamp' was identified as unnecessary and was dropped using `drop()`.
- **Renaming Columns:** Columns were renamed to enhance clarity and consistency in naming conventions.
- **Mapping Courses:** A mapping dictionary was utilized to categorize courses, enhancing data uniformity.
- **Extracting Numeric Year:** A new column, 'Numeric_Year_of_Study,' was created by extracting numeric values from the 'Year_of_Study' column.
- **Converting to Numeric Data Type:** The 'Numeric_Year_of_Study' column was converted to a numeric data type for numerical analysis.
- **Trimming Whitespaces:** Leading and trailing whitespaces were removed from the 'CGPA' column using the `strip()` method.
- **Categorizing CGPA:** The 'CGPA' column was categorized into ordered groups using predefined categories and specified order.

## Statistical Techniques
 - Utilized **central tendency** and **spread statistics** to describe the dataset.
 - Visualized the distribution of quantitative features using **histograms**.
 - Summarized categorical data using **count plots, pie charts and bar chart**.
 - Investigated categorical data associations using **contingency tables, proportions, and chi-square statistics**.

## Skills Applied

- **Data Cleaning**: Employed various techniques to clean and format data for analysis.
- **Descriptive Statistics**: Utilized central tendency and spread statistics to summarize data.
- **Data Visualization**: Employed seaborn and matplotlib for visualizing both quantitative and categorical data.
- **Statistical Testing**: Applied chi-square statistics to test associations between categorical variables.
- **Python Programming**: Implemented code in Python, utilizing Pandas, Seaborn, SciPy, and MatPlotLib libraries.
