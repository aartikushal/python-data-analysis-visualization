# 📊 Data Analysis & Visualization with Python

This project demonstrates the use of **Python** for **data analysis**, **preprocessing**, **feature engineering**, and **visualization** using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## 📝 Table of Contents

1. [Overview](#overview)  
2. [Dataset Exploration](#dataset-exploration)  
3. [NumPy Array Operations](#numpy-array-operations)  
4. [Data Preprocessing & Feature Engineering](#data-preprocessing--feature-engineering)  
5. [Data Transformation](#data-transformation)  
6. [Pandas DataFrame Manipulations](#pandas-dataframe-manipulations)  
7. [Data Visualization](#data-visualization)  
8. [Summary](#summary)  

---

## 🌟 Overview

This project covers:

- **Data exploration** with Pandas  
- **Array manipulations** and **vectorized operations** with NumPy  
- **Data preprocessing**: missing value handling, feature creation, scaling  
- **Data visualization**: line plots, scatter plots, histograms, bar charts  

---

## 📊 Dataset Exploration

```python
import pandas as pd

df = pd.read_csv("Mobiles Dataset (2025).csv", encoding='ISO-8859-1')
df.head()
df.info()
df.describe()
df.isnull().sum()
