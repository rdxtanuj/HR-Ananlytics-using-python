# HR Analytics: Employee Attrition Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) on an HR dataset to understand the factors that lead to employee attrition. By analyzing demographics, departmental trends, and work-life balance, this project aims to provide actionable insights for organizations to improve employee retention.

## Key Features
- **Departmental Distribution:** Analysis of how employees are spread across different business units (Sales, R&D, and HR).
- **Gender & Age Analysis:** Visualizing the workforce diversity and identifying age brackets most prone to leaving.
- **Attrition Metrics:** Calculation of the overall attrition rate and department-specific turnover.
- **Work-Life Balance Correlation:** Examining the relationship between employee satisfaction and their likelihood to stay.

## Technologies Used
- **Python 3.x**
- **Pandas:** Data manipulation and cleaning.
- **Matplotlib & Seaborn:** Data visualization and statistical plotting.
- **Jupyter Notebook:** Interactive environment for analysis.

## Dataset
The analysis is based on the `HR-Employee-Attrition.csv` dataset (included in this repository), which contains 1,470 employee records with 35 features, including:
- **Demographics:** Age, Gender, Marital Status.
- **Employment Details:** Department, Job Role, Monthly Income, Years at Company.
- **Psychological Factors:** Job Satisfaction, Relationship Satisfaction, Work-Life Balance.

## Visualizations Included
The notebook generates several plots to communicate findings:
1. **Count Plots:** Distribution of employees by Department and Gender.
2. **Histograms:** Age distribution across the workforce.
3. **Comparative Analysis:** Attrition rates segmented by business department.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hr-analytics-attrition.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas seaborn matplotlib
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HR-Analytics.ipynb
   ```

## Preliminary Findings
- The overall attrition rate for the organization is approximately **16.12%**.
- Research & Development is the largest department, while the Sales department shows significant attrition activity.
- Employees with lower "Work-Life Balance" scores show a higher propensity for attrition.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for suggestions.

## License
This project is licensed under the MIT License.
