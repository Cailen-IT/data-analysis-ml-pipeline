# Data Analysis & Machine Learning Pipeline

## Overview
This project demonstrates end-to-end data analysis using Python, focusing on:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Revenue analysis
- Data visualization

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Key Steps
- Data loading and inspection
- Data cleaning and transformation
- Feature engineering (Revenue calculation)
- Aggregated analysis by category
- Data visualization for insights

---

## Example Workflow

```python
import pandas as pd

df = pd.read_csv("data/sales_data.csv")

df["Date"] = pd.to_datetime(df["Date"])

df["Revenue"] = df["Units_Sold"] * df["Unit_Price"]

print(df.head())
```

---

## Key Insight
Revenue varies significantly across product categories, indicating strong category-level performance differences and potential business optimization opportunities.

---

## How to Run

```bash
pip install pandas matplotlib jupyter
jupyter notebook
```

---

## Author
BSc Information Technology Graduate (Data & Software Development Focus)