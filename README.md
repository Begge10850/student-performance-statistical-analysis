# Student Performance Statistical Analysis

This project presents a statistical analysis of student performance in Mathematics and Language. The analysis was prepared as part of an application report for the M.Sc. Data Science program at TU Dortmund University for Winter Semester 2026/2027.

The main goal of the project is to examine whether student scores differ by gender and by parental level of education. The dataset contains 486 students, with each student having scores in two subjects: Mathematics and Language.

## Research Questions

The analysis answers two main research questions:

1. Is there a statistically significant difference between male and female students in Mathematics and Language scores?
2. Is there a statistically significant difference in scores across parental education levels, and if so, which groups differ from each other?

## Dataset

The original dataset was provided in long format, where each student appeared twice: once for Mathematics and once for Language. The dataset contained 972 rows before reshaping.

After data preparation, the dataset was transformed into wide format with one row per student. The final analysis dataset contained:

- 486 students
- Mathematics score
- Language score
- Gender
- Parental level of education

The score variables range from 0 to 100.

## Methods Used

The analysis was conducted in Python using the following statistical methods:

- Descriptive statistics
- Data reshaping from long format to wide format
- Statistical visualizations
- Welch two-sample t-tests
- Cohen’s d effect size
- One-way ANOVA
- Tukey HSD post-hoc tests
- Eta-squared effect size
- Levene’s test for variance homogeneity
- Histogram-based distribution checks

## Tools and Libraries

The project uses:

- Python
- pandas
- matplotlib
- seaborn
- scipy
- statsmodels
- Jupyter Notebook

## Key Findings

The analysis found statistically significant gender differences in both subjects. Male students had a higher mean Mathematics score, while female students had a higher mean Language score.

The analysis also found statistically significant differences across parental education levels. Students whose parents had a high school level of education generally had lower average scores than students whose parents had higher education levels.

However, the effect sizes showed that parental education explained only a limited proportion of total score variation. Therefore, the findings should be interpreted as statistical associations rather than causal effects.

## Project Files

```text
research.ipynb