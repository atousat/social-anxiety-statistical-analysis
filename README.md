
# Social Anxiety Statistical Analysis

This project explores a social anxiety dataset and performs statistical analysis based on anxiety levels.  
The notebook focuses on understanding the data structure, identifying the target variable, and applying hypothesis testing to compare groups under different conditions.

---

## Project Overview

The goal of this project is to analyze a social anxiety dataset and investigate how anxiety-related features behave across different groups.

The notebook includes:
- data loading and inspection
- feature review and dataset understanding
- target variable identification
- statistical testing based on group assumptions
- hypothesis testing using both parametric and non-parametric methods

---

## Dataset

The project uses:

- `social_anxiety_dataset.csv`

The dataset includes features related to anxiety, stress, diet, family history, and the final anxiety label.

### Main Columns
- `Family History of Anxiety`
- `Stress Level (1-10)`
- `Diet Quality (1-10)`
- `Anxiety Level (1-10)`
- `Target`
- `is_Anxious`

---

## Target Variable

The notebook explicitly identifies:

- **`is_Anxious`**

as the target variable.

---

## Statistical Analysis

The statistical analysis followed a structured hypothesis testing workflow based on variable types and distribution assumptions.

**Numerical Variables**
- Normality assessment using the Shapiro–Wilk test.
- If the normality assumption was satisfied, an independent two-sample t-test was performed.
- If the data was not normally distributed, the Mann–Whitney U test was used as a non-parametric alternative.

**Categorical Variables**
- Associations between categorical variables and social anxiety were evaluated using the Chi-Square Test of Independence.
  
This methodology ensures that each statistical test is selected according to the characteristics of the data, providing reliable and valid comparisons across both numerical and categorical variables.

---

## Statistical Tests Used

- Shapiro–Wilk test (normality assessment)
- Independent two-sample t-test (parametric)
- Mann–Whitney U test (non-parametric)
- Chi-Square Test of Independence (categorical variables)
---

## Libraries Used

- NumPy
- Pandas
- Seaborn
- Matplotlib
- SciPy
- Scikit-learn

---

## Technologies

- Python
- Jupyter Notebook
- Statistical hypothesis testing
- Data visualization

---

## Project Structure
```bash
Social_Anxiety.ipynb
social_anxiety_dataset.csv
README.md
requirements.txt
