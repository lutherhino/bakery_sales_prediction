# Sales Forecasting for a Bakery Branch
Benedikt Luther
## Repository Link

https://github.com/lutherhino/bakery_sales_prediction.git

## Description

This project focuses on sales forecasting for a bakery branch, utilizing historical sales data spanning from July 1, 2013, to July 30, 2018, to inform inventory and staffing decisions. We aim to predict future sales for six specific product categories: Bread, Rolls, Croissants, Confectionery, Cakes, and Seasonal Bread. Our methodology integrates statistical and machine learning techniques, beginning with a baseline linear regression model to identify fundamental trends, and progressing to a sophisticated neural network designed to discern more nuanced patterns and enhance forecast precision. The initiative encompasses data preparation, crafting bar charts with confidence intervals for visualization, and fine-tuning models to assess their performance on test data from August 1, 2018, to July 30, 2019, using the Mean Absolute Percentage Error (MAPE) metric for each product category.

### Task Type

Regression

### Results Summary

Best Model: Improved Linear Model (Product-Specific Ridge/Gradient Boosting Regression)
Evaluation Metric: MAPE
Result by Category (Identifier):
Bread (1): 11.9% (MAE: 23.40)
Rolls (2): 29.7% (MAE: 58.19)
Croissant (3): 16.1% (MAE: 31.55)
Confectionery (4): N/A* (MAE: 20.22)
Cake (5): 21.2% (MAE: 44.59)
Seasonal Bread (6): 13.3% (MAE: 20.46)

Overall MAPE: 20.5%

*Note: Confectionery showed negative R² values, indicating poor model fit for this category. The MAPE calculation may not be reliable for this product group.
The improved linear model significantly outperformed both the baseline approaches and the neural network (MAPE: 20.6%), with particularly strong performance for Bread and Seasonal Bread categories.

## Documentation

1.  [**Data Import and Preparation**](0_DataPreparation/)
3.  [**Dataset Characteristics (Barcharts)**](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)
4.  [**Baseline Model**](2_BaselineModel/prediction_linear_regression_baseline.csv)
5.  [**Model Definition and Evaluation**](3_Model)
6.  [**Presentation**](4_Presentation/README.md)

## Cover Image
![alt text](logo.png)
