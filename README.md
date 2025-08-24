🛒 #BigBasket Products MiniProject – Exploratory Data Analysis (EDA)
📌 Project Overview

This project conducts an Exploratory Data Analysis (EDA) on the BigBasket Products dataset.
The dataset contains product-level information such as category, sub-category, brand, pricing, discount, and ratings.
The goal of this analysis is to uncover hidden patterns, clean inconsistencies, visualize trends, and derive actionable business insights.

🎯 Objectives

Data Understanding – Explore dataset structure, dimensionality, and attributes.

Data Cleaning – Handle missing values, duplicates, and inconsistent formatting.

Descriptive Statistics – Summarize numerical and categorical features.

Outlier Treatment – Detect and cap extreme values using robust statistical techniques.

Visualization – Apply charts and plots to identify meaningful patterns.

Insight Generation – Highlight product category dominance, brand concentration, and pricing gaps.

Business Recommendations – Provide actionable insights to support decision-making.

📂 Dataset Summary

Total Rows: ~27,555

Columns: 11

Key Attributes:

Product, Category, Sub-category, Brand

Sale Price, Market Price, Discount

Rating, Type, Description

The dataset exhibits real-world issues such as missing values, skewed price distributions, and rating outliers — making it suitable for a complete EDA process.

🛠 Tools & Technologies

Programming Language: Python 🐍

Libraries: Pandas, NumPy (data handling), Matplotlib, Seaborn (visualization)

Environment: Jupyter Notebook 📓

📝 Methodology & Steps Followed

Data Import & Inspection

Load dataset into Pandas DataFrame.

Review data types, shape, and preliminary statistics.

Data Cleaning

Handle missing values and duplicates.

Standardize categorical fields (brand names, categories).

Feature Engineering

Calculate discount percentage.

Create derived variables for analysis.

Descriptive Analysis

Explore numerical distributions (mean, median, IQR).

Summarize categorical distributions (top brands, categories).

Outlier Detection & Treatment

Apply IQR method to detect price/rating outliers.

Cap extreme values to reduce skewness.

Visualization

Univariate: histograms, boxplots (price distribution).

Bivariate: bar plots, heatmaps (category vs price, discount vs brand).

Multivariate: correlation analysis among numerical features.

Insight Extraction

Identify leading brands and product categories.

Compare market vs sale price differences.

Assess rating distribution for customer feedback trends.

📊 #Key Insights

Category Concentration: A few top categories dominate the product listings.

Brand Dominance: Limited brands contribute disproportionately (Pareto effect).

Pricing Gap: Notable variance between market and sale price, indicating heavy discounting strategies.

Customer Ratings: Average rating ~3.9; extreme ratings adjusted for reliability.

🏁 #Conclusion

The EDA exercise provided cleaned, structured, and well-understood data suitable for further analysis and modeling.
Key insights highlight brand/category dominance, discounting practices, and consumer rating behavior, which can inform pricing strategies, inventory planning, and marketing decisions.

