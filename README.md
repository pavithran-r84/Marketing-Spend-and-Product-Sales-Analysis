# Marketing Spend and Product Sales Analysis

## Project Overview

This project revisits a marketing dataset that was previously analyzed as part of an earlier analytics project. While the earlier analysis focused mainly on data preparation, dashboard creation, and reporting, this project approaches the dataset from a different perspective.

The focus of this analysis is to understand the relationship between marketing spend and product sales through regression analysis and business-driven questions. Rather than concentrating only on visualizing the data, the objective was to identify which marketing activities show a stronger relationship with sales performance and what insights can be drawn from the results.

Using Linear Regression, Polynomial Regression, and Multiple Regression models, the analysis was performed at both the channel level and category level to better understand marketing performance and interpret the findings through a business lens.

---

## Business Questions

The project was designed to answer the following questions:

1. Does advertising spend influence product sales?
2. Would a more complex relationship explain product sales better?
3. Which marketing channels have the greatest impact on product sales?
4. Which marketing categories contribute most to product sales?

---

## Dataset Information

The dataset contains spending information across multiple marketing channels, including:

* TV
* Billboards
* Google Ads
* Social Media
* Affiliate Marketing
* Influencer Marketing

Target Variable:

* Product Sold

Additional Feature Created:

* Total Spend

Marketing categories were also created for broader analysis:

| Category    | Channels                 |
| ----------- | ------------------------ |
| Traditional | TV, Billboards           |
| Digital     | Google Ads, Social Media |
| Affiliate   | Affiliate Marketing      |
| Partnership | Influencer Marketing     |

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Power BI
* GitHub

---

## Methodology

The analysis was conducted in four stages:

### 1. Linear Regression

Used to evaluate the relationship between total advertising spend and product sales.

### 2. Polynomial Regression

Used to test whether a more complex relationship existed between advertising spend and product sales.

### 3. Multiple Regression (Channel Level)

Used to identify the impact of individual marketing channels on product sales.

### 4. Multiple Regression (Category Level)

Used to evaluate the contribution of broader marketing categories to product sales.

---

## Key Insights

### Insight 1

Advertising spend showed a strong relationship with product sales, with the Linear Regression model achieving an R² score of 0.847.

### Insight 2

Polynomial Regression produced a similar R² score and did not provide a meaningful improvement over the simpler Linear Regression model.

### Insight 3

Affiliate Marketing showed the strongest contribution among all marketing channels, followed by Billboards and Social Media.

### Insight 4

Affiliate Category showed the highest contribution among all marketing categories, indicating a consistent pattern across both channel-level and category-level analysis.

---

## Repository Structure

* Data Files
* Colab Notebook
* Analytical Report
* Insight Visualizations
* Project Documentation

---

## Learning Outcomes

Through this project, I gained experience in:

* Data preparation and feature engineering
* Regression modeling
* Model evaluation using R²
* Business-focused analysis
* Insight generation
* Analytical reporting

---

## Dataset Source

The dataset used in this project was obtained from Kaggle and was used for learning, analysis, and portfolio development purposes.
