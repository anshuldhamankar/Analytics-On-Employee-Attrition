# Employee Attrition Analysis

A comprehensive data analysis project focused on understanding employee attrition patterns using machine learning and statistical analysis techniques.

## Project Overview

This project analyzes HR employee attrition data to identify key factors that contribute to employee turnover. The analysis includes exploratory data analysis (EDA), visualization, and predictive modeling to help organizations understand and predict employee attrition.

## Dataset

The project uses the `HREmployeeAttrition.csv` dataset containing employee information with 35 features including:
- Demographics (Age, Gender, Marital Status)
- Job-related factors (Job Role, Department, Job Level)
- Compensation (Monthly Income, Daily Rate, Hourly Rate)
- Work environment (Work-Life Balance, Job Satisfaction)
- Career progression (Years at Company, Years in Current Role)

## Key Features

- **Data Preprocessing**: Handling missing values and data type conversions
- **Exploratory Data Analysis**: Statistical analysis and visualization of attrition patterns
- **Feature Engineering**: Creating new variables for better model performance
- **Machine Learning**: Decision tree analysis for predicting employee attrition
- **Visualization**: Comprehensive charts and graphs using matplotlib and seaborn

## Files Structure

```
├── Analysis.ipynb                          # Main analysis notebook
├── Employee-Attrition-Analysis_DT.ipynb   # Decision tree analysis
├── Attrition_Analysis_report.docx         # Detailed analysis report
├── HREmployeeAttrition.csv                 # Dataset (not included)
└── README.md                               # This file
```

## Key Findings

Based on the analysis, several important patterns emerge:

### Age Demographics
- Median employee age is 36 years
- Employees who leave the company are predominantly under 40 years old
- Employees who stay are typically between 32-40 years old

### Compensation Impact
- Employees with lower daily rates show higher attrition rates
- Monthly income is inversely correlated with attrition likelihood
- Compensation appears to be a significant factor in retention

## Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## Installation & Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd Analytics-On-Employee-Attrition-main
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `Analysis.ipynb` to start exploring the analysis

## Usage

1. **Data Loading**: The notebook loads the HR employee attrition dataset
2. **Data Exploration**: Examine data structure, missing values, and basic statistics
3. **Visualization**: Generate various plots to understand attrition patterns
4. **Analysis**: Run statistical analysis to identify key factors
5. **Modeling**: Apply machine learning techniques for prediction

## Analysis Workflow

1. **Data Import and Cleaning**
   - Load the dataset
   - Check for missing values
   - Data type conversions

2. **Exploratory Data Analysis**
   - Statistical summaries
   - Distribution analysis
   - Correlation analysis

3. **Feature Analysis**
   - Age distribution analysis
   - Compensation impact study
   - Job satisfaction correlation

4. **Visualization**
   - Box plots for numerical variables
   - Count plots for categorical variables
   - Distribution plots

## Results & Insights

The analysis reveals that employee attrition is influenced by multiple factors, with age and compensation being primary indicators. The findings can help HR departments develop targeted retention strategies.

## Contributing

Feel free to contribute to this project by:
- Adding new analysis techniques
- Improving visualizations
- Enhancing the machine learning models
- Adding more comprehensive documentation

## License

This project is available for educational and research purposes.

## Contact

For questions or suggestions regarding this analysis, please feel free to reach out.

---

*This analysis provides insights into employee attrition patterns and can serve as a foundation for developing effective employee retention strategies.*