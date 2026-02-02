# Lab 1: Types of Variate Regression using Iris Dataset

## Overview
This lab focuses on understanding and implementing **Univariate, Bivariate, and Multivariate Linear Regression**
using the **Iris dataset**.  
The complete implementation is provided in a single Jupyter Notebook (`lab 1a.ipynb`), and the regression
outputs are saved as image files for documentation and evaluation.

The lab demonstrates how the number of independent variables affects model behavior and interpretation.

---

## Objectives
- To understand the concept of variate regression
- To implement univariate, bivariate, and multivariate linear regression
- To visualize regression results using plots
- To analyze relationships between independent and dependent variables

---

## Dataset
- **Dataset Name:** Iris Dataset
- **File Used:** `iris.csv`
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Dependent Variable:**
  - Sepal Length

---

## Tools and Libraries Used
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Regression Experiments

### 1. Univariate Regression
- **Independent Variable:** One feature
- **Dependent Variable:** Sepal Length
- Demonstrates regression with a single predictor.
- Output visualizes the regression line with data points.

**Output File:**
- `univariate_regression.png`

---

### 2. Bivariate Regression
- **Independent Variables:** Two features
- **Dependent Variable:** Sepal Length
- Shows how two predictors jointly influence the target variable.
- Results are visualized using a 3D regression plot.

**Output File:**
- `bivariate_regression.png`

---

### 3. Multivariate Regression
- **Independent Variables:** More than two features
- **Dependent Variable:** Sepal Length
- Demonstrates real-world regression with multiple predictors.
- Actual values are compared with predicted values.

**Output File:**
- `multivariate_regression.png`

---

## Output Visualizations Summary

| Image File Name | Description |
|-----------------|-------------|
| `univariate_regression.png` | Regression using one independent variable |
| `bivariate_regression.png` | Regression using two independent variables |
| `multivariate_regression.png` | Regression using multiple independent variables |

---

## Files Included

| File Name | Description |
|----------|-------------|
| `lab 1a.ipynb` | Complete implementation of all regression types |
| `lab 1a - types of variate regression.pdf` | Lab reference / problem statement |
| `univariate_regression.png` | Output of univariate regression |
| `bivariate_regression.png` | Output of bivariate regression |
| `multivariate_regression.png` | Output of multivariate regression |
| `README.md` | Documentation for Lab 1 |

---

## Conclusion
This lab clearly demonstrates the progression from univariate to multivariate regression.
By increasing the number of independent variables, the model’s ability to represent
complex relationships improves, making multivariate regression more suitable for real-world datasets.

---

## How to Run
1. Open `lab 1a.ipynb` in Jupyter Notebook or VS Code
2. Ensure the Iris dataset is accessible in the notebook
3. Run all cells sequentially
4. Observe regression outputs and generated plots

---

## Author
**Name:** Kamalesh S P<br>
**Course:** Fundamentals of Machine Learning<br>
**Lab:** Lab 1 – Types of Variate Regression<br>
