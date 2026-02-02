# LAB0 – Iris Dataset Exploratory Data Analysis

## Overview
This lab demonstrates **basic exploratory data analysis (EDA)** on the **Iris dataset** using Python.  
All analysis and visualizations are implemented inside **`demo.ipynb`**, with plots saved as image files for reference.

The objective is to understand feature distributions and relationships between variables using simple, interpretable visualizations.

---

## Files in This Repository

| File Name | Description |
|----------|-------------|
| `demo.ipynb` | Jupyter Notebook containing the complete EDA workflow |
| `iris.csv` | Iris dataset used for analysis |
| `pairplot_iris.png` | Pairwise relationships between all numerical features |
| `sepal_length_distribution.png` | Distribution of sepal length |
| `sepal_width_distribution.png` | Distribution of sepal width |
| `sepal_width_vs_petal_width.png` | Relationship between sepal width and petal width |
| `README.md` | Documentation for LAB0 |

---

## Dataset Description
- **Dataset:** Iris Dataset  
- **Source File:** `iris.csv`  
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Classes:**
  - Setosa
  - Versicolor
  - Virginica

---

## Tools & Libraries Used
- Python 3
- pandas
- numpy
- matplotlib
- seaborn

---

## Exploratory Data Analysis Performed

The following analyses are carried out in `demo.ipynb`:

### 1. Feature Distributions
- Sepal length distribution
- Sepal width distribution  
These plots help identify spread, central tendency, and variation across samples.

### 2. Feature Relationships
- Sepal width vs petal width scatter plot  
Used to observe correlation and separation patterns.

### 3. Pairwise Analysis
- Pairplot covering all numerical features  
Provides a high-level overview of inter-feature relationships and class separability.

All plots are saved as `.png` files and included in the repository.

---

## How to Run
1. Ensure `iris.csv` is in the same directory as `demo.ipynb`
2. Open `demo.ipynb` using Jupyter Notebook or VS Code
3. Run cells sequentially from top to bottom
4. View generated visualizations in the notebook and image files

---

## Outcome
- Basic structure and behavior of Iris features are clearly visualized
- Relationships between variables are easy to interpret
- Dataset shows good class separability in pairwise plots

---

## Conclusion
This lab provides a clean and beginner-friendly introduction to **exploratory data analysis** using the Iris dataset.  
It establishes a solid foundation for future machine learning or statistical modeling tasks.

---

## Author
**Name:** Kamalesh S P<br>
**Course:** Fundamentals of Machine Learning<br>
**Lab:** Lab 0 – Dataset Manupulation<br>
