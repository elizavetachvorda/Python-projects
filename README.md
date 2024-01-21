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

## Analysis Highlights

### Gender Proportions
The gender distribution is nearly equal, with males at 50.52% and females at 49.48%. This balance enhances model representativeness.

### Average Insurance Charges by Gender
On average, males pay slightly more than females ($13956.75 vs. $12569.58), indicating a gender-based discrepancy in insurance charges.

### Average Age by Gender
Average ages for males and females are approximately 39 and 40, respectively. Age alone may not significantly contribute to the gender-based charge difference.

### Children Discrepancy in Charges
The number of children influences insurance cost discrepancies. Males have lower costs for up to three children, while females have higher costs with four or five children.

### BMI Distribution
More than 55% of males are classified as obese, explaining higher insurance costs. Females have a slight predominance in overweight individuals.

### Smoker Percentage
Males exhibit a significantly higher smoking prevalence (23.52% vs. 17.37% in females), contributing to potential insurance cost differences.

## Conclusion

The analysis reveals gender-based discrepancies in insurance charges, influenced by factors such as the number of children, obesity prevalence, and smoking habits. Insurers can use these insights to refine pricing strategies and promote healthier lifestyles, potentially reducing insurance costs.
