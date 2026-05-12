
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

The analysis follows a structured hypothesis testing workflow:

1. **Normality check** using the **Shapiro–Wilk test**
2. If both groups satisfy normality assumptions:
   - Apply an **independent two-sample t-test**
3. If the data does **not** follow a normal distribution:
   - Apply the **Mann–Whitney U test** as a non-parametric alternative

This approach ensures valid statistical comparisons regardless of data distribution.

---

## Statistical Tests Used

- Shapiro–Wilk test (normality assessment)
- Independent two-sample t-test (parametric)
- Mann–Whitney U test (non-parametric)

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
