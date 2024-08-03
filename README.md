# E-commerce-Customer-Satisfactin-Analysis


This repository contains analyses and visualizations related to customer satisfaction for e-commerce platforms, focusing on eBay and Amazon, and comparing them with industry best practices and competitors.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Insights](#dataset-insights)
- [Regression Analysis](#regression-analysis)
- [Summary of Analysis and Findings](#summary-of-analysis-and-findings)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Conclusion](#conclusion)


## Introduction

In this project, we perform a comprehensive analysis of customer satisfaction metrics for e-commerce platforms, particularly eBay and Amazon. The analysis includes:
1. Comparing performance with industry best practices.
2. Selecting key variables to predict customer satisfaction.
3. Building and refining linear regression models.
4. Deriving actionable insights to improve customer satisfaction.


## Dataset Insights

### Case5-Data.xlsx
This dataset contains customer satisfaction survey results for eBay and its competitors. The key attributes in the dataset include:

1. **Customer Satisfaction**: Overall satisfaction score given by customers.
2. **Willingness to Recommend**: Likelihood of customers recommending the platform to others.
3. **Average Customer Spend**: Average amount spent by customers per visit.
4. **Frequency of Visit**: How often customers visit the platform within a specific time frame.
5. **Key Performance Indicators (KPIs)**: Various metrics used to measure the platform's performance in areas such as product quality, ease of navigation, delivery options, and return policies.

### Key Insights
- **Customer Satisfaction**: Analyzed how customer satisfaction varies across different platforms and how eBay's satisfaction scores compare to industry best practices.
- **Predictive Modeling**: Identified the most significant variables affecting customer satisfaction using regression analysis.
- **Performance Comparison**: Compared eBay's performance with Amazon and other competitors, highlighting areas where eBay excels and areas needing improvement.
- **Actionable Insights**: Derived specific recommendations for eBay to improve customer satisfaction based on the regression model's findings.

## Regression Analysis

### Methodology
The regression analysis involved building and refining linear regression models to predict customer satisfaction based on various independent variables. The process included:
1. **Feature Selection**: Choosing relevant variables that are likely to influence customer satisfaction.
2. **Model Building**: Constructing linear regression models using the selected features.
3. **Model Evaluation**: Assessing the models using error metrics such as Mean Squared Error (MSE) and R-squared values.
4. **Insights Derivation**: Interpreting the model coefficients to derive actionable insights.

### Key Variables
The following variables were considered for the regression analysis:
1. **Price given quality**: The perceived value of products.
2. **Sufficiency of product information**: Availability of detailed product information.
3. **Ease of comparing products**: How easily customers can compare different products.
4. **Range of delivery options**: The variety of delivery methods available.
5. **Ease of tracking your order**: How easily customers can track their orders.
6. **Return and exchange policies**: Flexibility and ease of returning or exchanging products.

### Models Built
Several linear regression models were built and evaluated to find the best fit for predicting customer satisfaction. Key models include:
1. **Full Model**: Using all selected variables.
2. **Reduced Model**: Using a subset of variables based on statistical significance and model performance.

## Summary of Analysis and Findings

### Visualizations
A series of visualizations were created to compare the performance of eBay to the best practices of the industry and the average:
- **Bar Plot**: Highlighted areas where eBay is performing better or worse compared to the industry average and best practices.
- **Box Plots**: Showed the variability in customer satisfaction metrics between eBay and the industry.

### Selected Variables for Predicting Customer Satisfaction
The following variables were selected based on their significance in influencing customer satisfaction:
1. **Product Accuracy**
2. **Information Sufficiency**
3. **Delivery Timeliness**
4. **Website Security**
5. **Return Policy**
6. **Checkout Ease**
7. **Navigation Ease**
8. **Promotions Attractiveness**
9. **Feedback Availability**
10. **Interest Variety**

### Regression Analysis Results
- **eBay Model**: The most impactful features for eBay were return policy, special requests ease, feedback availability, cart management ease, product accuracy, and interest variety.
- **Amazon Model**: The most impactful features for Amazon were interest variety, compare ease, website security, delivery range, delivery timeliness, and feedback availability.

### Insights and Recommendations
- **eBay**:
  - Focus on improving return policies and special requests handling to enhance customer satisfaction.
  - Address lower-rated areas such as checkout ease and delivery information clarity.
- **Amazon**:
  - Enhance the variety of products and ease of comparing products to boost customer satisfaction.
  - Focus on maintaining high website security and providing clear delivery information.

### Common Predictors
- **Interest Variety** and **Feedback Availability** were common significant predictors for both eBay and Amazon, indicating their importance in customer satisfaction across different platforms.

### Tools and Technologies Used
Python libraries: Pandas for data manipulation, Matplotlib and Seaborn for visualization, and SciPy and scikit-learn for statistical testing and modeling.
Google Colab Notebooks for interactive analysis and documentation.

### Conclusion
The case study provided valuable insights into customer purchase patterns and device usage for eBay and Amazon. By leveraging these insights, both platforms can better tailor their marketing strategies and technological enhancements to meet the evolving needs of their customer base, ultimately driving growth and customer satisfaction.
