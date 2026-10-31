# Statistical Analysis and Hypothesis Testing in Python

## Project Overview
This project focuses on performing statistical analysis and hypothesis testing using Python on the Titanic passenger dataset. The main objective is to investigate whether passenger sex had a statistically significant association with survival.

## Objectives
- Explore and understand the Titanic dataset.
- Perform data cleaning and exploratory data analysis.
- Calculate survival counts and percentages.
- Apply the Chi-Square Test of Independence.
- Perform Fisher's Exact Test as a supplementary test.
- Calculate Cramér's V to measure association strength.
- Estimate a 95% confidence interval for the difference in survival rates.
- Visualize findings using Python libraries.

## Dataset
- **Dataset:** Titanic Passenger Dataset
- **Source:** [Titanic Dataset on GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Records:** 891 passengers
- **Features:** 12 columns

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Hypotheses
- **Null Hypothesis (H0):** Passenger sex and survival are independent.
- **Alternative Hypothesis (H1):** Passenger sex and survival are associated.

## Statistical Methods
1. Descriptive Statistical Analysis
2. Chi-Square Test of Independence
3. Fisher's Exact Test
4. Cramér's V
5. 95% Confidence Interval

## Key Findings
- Female survival rate: approximately 74.2%.
- Male survival rate: approximately 18.9%.
- Chi-Square statistic: approximately 263.05.
- P-value: approximately 3.71 × 10⁻⁵⁹.
- Cramér's V: approximately 0.543.

The results indicate a strong statistical association between passenger sex and survival in the Titanic dataset.

## Project Structure
```text
Week_3_Statistical_Hypothesis_Testing/
│
├── Week3_Statistical_Hypothesis_Testing.ipynb
├── README.md
└── figures/
    ├── 01_survival_rate_by_sex.png
    ├── 02_survival_counts_by_sex.png
    └── 03_expected_counts_heatmap.png
```

## How to Run
1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries if they are not already available.
4. Run all notebook cells.
5. Review the statistical results and generated visualizations.

## Conclusion
The hypothesis testing results show that passenger sex was strongly associated with survival on the Titanic. This project demonstrates how Python-based statistical techniques can be used to analyze real-world data, test hypotheses, and communicate meaningful insights.

## Author
Created as part of the Week 3 Data Science with Python project.
