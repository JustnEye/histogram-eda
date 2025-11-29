# Histogram EDA

This project explores the fundamentals of Exploratory Data Analysis (EDA) using histograms in Python.

## Goals
- Visualize data distributions using Matplotlib and Seaborn.
- Understand outliers, skewness, and bin sizes.
- Compare histogram and kernel density estimation (KDE).

## Tools
- Python 3.x
- pandas
- matplotlib
- seaborn

## Repository Structure
histogram-eda/
├── notebooks/
│ └── 01_basic_histograms.ipynb
└── README.md

## Example
A basic histogram of the Iris dataset:

```python
sns.histplot(df["sepal_length"], bins=20, kde=True)