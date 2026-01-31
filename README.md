# Cafe Sales EDA ☕📊
> As part of the ***2026 Monthly Personal Projects**  /  January 1 of 12*

Exploratory data analysis project on cafe transaction data to uncover sales patterns, top-performing items, and time-based trends. The goal is to turn raw point-of-sale data into clear, actionable insights.

---

## Project Objective

The goal of this project is to:
- Clean a deliberately “dirty” cafe sales dataset
- Explore sales volume and revenue behavior over time
- Identify top-performing products
- Derive simple, interpretable metrics that reflect customer purchasing patterns

This project is intentionally scoped to **descriptive analysis and visualization**, without predictive modeling.

---

## Dataset

**Source:**  
Cafe Sales – Dirty Data for Cleaning Training  
https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training

**Description:**  
The dataset contains cafe transaction records, including:
- Transaction timestamps
- Product names
- Quantities sold
- Item prices and transaction totals

The data includes common real-world issues such as missing values and inconsistent formatting, making it suitable for data cleaning and exploratory analysis practice.

---

## Approach

### 1) Data Cleaning

The following cleaning steps were performed in the notebook:
- Identification and handling of missing or invalid values
- Conversion of timestamp columns into usable datetime features
- Validation and correction of numeric fields such as quantity and price
- Basic column standardization to enable grouping and aggregation

The objective of the cleaning process was to make the dataset **analysis-ready** while preserving as much original information as possible.

---

### 2) Exploratory Data Analysis (EDA)

The exploratory analysis focuses on:
- Summary statistics and distributions of key numeric variables
- Comparison of sales volume versus revenue across products
- Time-based aggregation of sales activity
- Examination of how transaction behavior changes throughout the day

The analysis is descriptive and intended to surface intuitive patterns rather than test formal hypotheses.

---

### 3) Visualization & Insights

The notebook includes visualizations that support the following insights:

- **Top Products by Revenue and Quantity**  
  A small subset of products accounts for a disproportionately large share of total revenue. Rankings by quantity sold differ from rankings by revenue, indicating that price plays a significant role in overall performance.

- **Sales Activity Over Time**  
  Aggregated sales show clear time-of-day patterns, with identifiable peak periods of activity. This suggests predictable customer flow rather than uniform demand throughout the day.

- **Average Transaction Value by Hour of Day**  
  While transaction volume is higher during peak hours, average transaction value varies across the day. Certain periods show fewer transactions but higher average spend per transaction, suggesting differences in customer purchasing behavior depending on time of day.

All visualizations are static and designed to support interpretability rather than interactive exploration.

---

## Results Summary

Key findings from the analysis:
- Sales activity follows clear and repeatable time-based patterns.
- A small number of products drives the majority of revenue.
- High sales volume does not always correspond to high revenue, emphasizing the importance of price.
- Average transaction value varies throughout the day, indicating that customer spending behavior changes over time, not just transaction frequency.

---

## Reproducibility

All data cleaning, aggregation, and visualization steps are documented in the notebook.  
Running the notebook from top to bottom reproduces the full analysis.

---

## Possible Extensions (Out of Scope)

To keep the project tightly scoped, the following were intentionally not explored:
- Market basket or product co-occurrence analysis
- Predictive or forecasting models
- Interactive dashboards or deployed applications
- Customer segmentation or cohort analysis

These represent natural next steps but were not required to meet the objectives of this project.

---

## Author

Jorge
