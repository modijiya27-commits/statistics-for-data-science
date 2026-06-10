# Statistics with Python: EDA, Visualization & Hypothesis Testing

## Overview

This project combines concepts learned during Days 23, 25, and 27 of my 50-Day Data Analytics Challenge.

The notebook covers the complete workflow from exploratory data analysis and visualization to hypothesis testing using a real-world IMDb movie dataset.

The goal was to understand data distributions, identify patterns, explore relationships between variables, and validate findings using statistical testing.

---

## Topics Covered

### Day 23 – Data Visualization & Data Understanding

- Histograms
- Box Plots
- Scatter Plots
- Category Analysis
- Outlier Detection
- Distribution Analysis

### Day 25 – IMDb Dataset Analysis

- Dataset Exploration
- Rating Distribution
- Genre-Based Analysis
- Relationship between Votes and Ratings
- Statistical Observations

### Day 27 – Hypothesis Testing

- Null & Alternative Hypothesis
- Significance Level
- P-Value Interpretation
- Type I & Type II Errors
- Independent Two-Sample T-Test

---

## Dataset

IMDb Movies Dataset

Key Features Used:

- Genre
- Rating
- Votes
- Runtime

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Exploratory Data Analysis

### Rating Distribution

A histogram with KDE was used to examine the distribution of movie ratings.

### Q-Q Plot

A Q-Q plot was used to assess normality assumptions before performing hypothesis testing.

### Outlier Detection

Box plots were used to identify potential outliers and understand data spread.

### Relationship Analysis

Scatter plots were used to explore relationships between ratings and other variables.

---

## Hypothesis Testing

### Research Question

Do Drama and Comedy movies have significantly different average ratings?

### Null Hypothesis (H₀)

There is no significant difference between the average ratings of Drama and Comedy movies.

### Alternative Hypothesis (H₁)

There is a significant difference between the average ratings of Drama and Comedy movies.

---

## Results

### Average Ratings

| Genre | Average Rating |
|---------|--------------|
| Drama | 5.999 |
| Comedy | 5.737 |

### Independent T-Test

| Metric | Value |
|----------|---------|
| T-Statistic | 6.827 |
| P-Value | 9.47 × 10⁻¹² |

---

## Conclusion

Since the p-value is significantly lower than the significance level (0.05), the null hypothesis was rejected.

The analysis suggests that Drama and Comedy movies have statistically different average ratings, with Drama movies receiving higher ratings on average within this dataset.

---

## Key Learnings

- Data Visualization
- Distribution Analysis
- Outlier Detection
- Correlation Exploration
- Normality Assessment
- Hypothesis Testing
- Statistical Decision Making
- Applying Statistics with Python

---

## Project Structure

Statistics_Project/
│
├── statistics_notebook.ipynb
├── README.md
└── imdb_dataset.csv

---

## Author

Jiya

50-Day Data Analytics Challenge
