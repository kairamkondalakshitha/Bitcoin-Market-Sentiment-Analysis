# Bitcoin Market Sentiment Analysis

## Objective

This project explores the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using Hyperliquid historical trading data.

## Datasets

### 1. Historical Trader Data

Contains:

- Account
- Coin
- Execution Price
- Size USD
- Side
- Closed PnL
- Fee
- Timestamp

### 2. Fear & Greed Index

Contains:

- Timestamp
- Classification
- Value

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Timestamp Conversion
4. Dataset Merging
5. Exploratory Data Analysis
6. Data Visualization
7. Machine Learning
8. Insights

---

## Exploratory Data Analysis

Performed:

- Missing Value Analysis
- Profit Distribution
- Trade Distribution
- Average Profit
- Average Trade Size
- Fee Analysis
- Correlation Heatmap
- Feature Importance

---

## Machine Learning

Model:

Random Forest Classifier

Accuracy:

81.76%

---

## Key Findings

- Greed market sentiment generated the highest average profit.
- Fear also produced positive returns.
- Execution Price was the most influential feature.
- Trading Fee and Trade Size significantly affected profitability.
- Market sentiment had a smaller but measurable effect.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Conclusion

Execution Price, Fee, and Trade Size have a stronger influence on profitability than sentiment alone.

The Fear & Greed Index can improve trading decisions when combined with other trading indicators.