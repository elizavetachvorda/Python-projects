# U.S.-Medical-Insurance-Costs-Project

This data analysis project explores medical insurance costs across various demographic groups using Python. By utilizing fundamental Python skills, the insurance.csv dataset is analyzed to gain insights into the factors influencing insurance charges.
The csv.DictReader class is employed to read the CSV file, enabling convenient manipulation and analysis of the data.

### Dataset Columns:

age: Age of the primary beneficiary
sex: Gender of the insurance contractor (female, male)
bmi: Body mass index
children: Number of children covered by health insurance
smoker: Smoking status
region: Residential area in the U.S.
charges: Individual medical costs billed by health insurance
The dataset contains no missing data.

## Skills demonstrated in data loading and organization:
- **CSV File Handling:** Read a CSV file ('insurance.csv') using the `csv` module in Python.
- **Data Structure:** Created a list (`data`) to store patient records, and each record represented as a dictionary.

## Skills demonstrated in the InsuranceAnalysis class:
- **Class Definition:** Defined a class `InsuranceAnalysis` to encapsulate methods for data analysis.
- **Data Manipulation:** Extracted relevant information from the dataset using dictionary keys.
- **For Loops:** Iterated through the dataset to calculate various statistics.

## Methods within InsuranceAnalysis class:

### gender_proportions
- **Data Aggregation:** Calculated proportions of males and females within the dataset.
- **String Formatting:** Used string formatting to present the results in a readable manner.

### average_charge_per_gender
- **Conditional Statements:** Employed if-else statements to differentiate between male and female records.
- **Numerical Operations:** Calculated average insurance charges for both males and females.
- **String Formatting:** Formatted the results for clear presentation.

### average_age_per_gender
- **Conditional Statements:** Differentiated between male and female records using if-else statements.
- **Numerical Operations:** Calculated average ages for both males and females.
- **String Formatting:** Formatted the results for clarity.

### children_discrepancy
- **Data Grouping:** Grouped data based on the number of children.
- **List Comprehension:** Utilized list comprehension to calculate average charges within each group.
- **Dictionary Operations:** Created a dictionary to store discrepancies.
- **Sorting:** Sorted the dictionary by keys in ascending order.

### bmi_distribution
- **Conditional Statements:** Categorized individuals based on BMI into overweight and obese categories.
- **Proportion Calculations:** Calculated proportions of overweight and obese individuals for both genders.
- **String Formatting:** Formatted results for clear presentation.

### smoker_percentage
- **Conditional Statements:** Separated records based on gender and smoking status.
- **Percentage Calculations:** Calculated the percentage of smokers for both males and females.
- **String Formatting:** Formatted results for clear presentation.


