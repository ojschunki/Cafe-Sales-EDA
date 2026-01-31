# Cafe Sales EDA ☕📊
> As part of the ***2026 Monthly Personal Projects**  /  January 1 of 12*

Exploratory data analysis project on cafe transaction data to uncover sales patterns, top-performing items, and time-based trends. The goal is to turn raw point-of-sale data into clear, actionable insights.

## Project Goals
This project focuses on:
- Cleaning and validating sales transaction data
- Understanding revenue and demand drivers
- Identifying time-based trends (daily / weekly patterns)
- Summarizing insights in a way that could inform operational decisions (staffing, inventory, promotions)

## Key Questions
Some of the questions explored:
1. What are the best-selling products by quantity and by revenue?
2. When are peak sales periods (by hour/day)?
3. How does average transaction value change over time?
4. Are there product combinations or categories that frequently occur together? *(Optional extension)*

## Dataset
The dataset contains cafe sales transactions (e.g., timestamps, items, quantities, and prices).  
If the dataset source is public (Kaggle/UCI/etc.), add it here.

**Notes**
- Some values may require cleaning (missing values, formatting issues, inconsistent categories).
- All cleaning steps are documented in the notebook so results are reproducible.

## Approach
### 1) Data Cleaning
Typical steps include:
- Handling missing / invalid entries
- Converting date/time columns into usable features
- Standardizing product names/categories (if needed)
- Checking for outliers (quantity, price, totals)

### 2) Exploratory Analysis (EDA)
- Summary statistics and distributions
- Sales volume vs revenue comparisons
- Time-series style analysis (by day / hour)
- Category and product breakdowns

### 3) Visualization
Visualizations are used to support insights, such as:
- Top items by revenue / units sold
- Sales trend lines over time
- Heatmaps of activity by day-of-week and hour

## Results Summary (Fill In)
Add 3–5 bullets after you finalize your notebook:
- Peak sales occur around **[X time/day]**
- The top revenue item is **[Item]**, contributing **[Y%]** of revenue
- Average transaction value is higher on **[weekday/weekend]**
- A small set of products drives most sales (Pareto-style behavior)

## Repository Structure
Cafe-Sales-EDA/
├── eda.ipynb
├── data/
| └── dirty_cafe_sales.csv
└── README.md
