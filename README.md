# 📊 Exploratory Data Analysis (EDA) – Bivariate and Multivariate Analysis

This project demonstrates *Bivariate* and *Multivariate* analysis techniques in Exploratory Data Analysis (EDA) for Machine Learning datasets.

---

## 🔍 What is EDA?

Exploratory Data Analysis (EDA) is the process of analyzing data sets by summarizing their main characteristics using visual methods.

---

## 📈 Bivariate Analysis

*Bivariate Analysis* involves the analysis of two variables to find relationships between them.

### 🔹 Techniques Used:

- *Scatter Plot*: To study relationship between two continuous variables.
- *Box Plot*: For comparing distributions across a categorical variable.
- *Correlation Matrix*: To measure the strength and direction of relationships.
- *Bar Plot*: For comparing a numerical variable against a category.

### 📌 Example:
```python
import seaborn as sns
import matplotlib.pyplot as plt

# Scatter plot between Age and Salary
sns.scatterplot(x='Age', y='Salary', data=df)
plt.title("Age vs Salary")
plt.show()
