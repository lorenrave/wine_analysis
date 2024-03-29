# Wine Review Analysis

![los-mejores-vinos-por-menos-de-10-euros-portada-800x533](https://github.com/lorenrave/wine_analysis/assets/108484210/a0f318dc-ae93-4975-bda2-0728898ed8d9)


## About the project

This project explores a dataset containing 129,907 wine reviews from various countries. Utilizing standard data science skills, we aim to clean, analyze, visualize, and interpret the data, with the objective of providing scientifically-based insights derived from observed patterns in the data.

The purpose of conducting a wine review analysis is to understand Consumer Orientation, Identify Trends, and Provide Feedback for producers.

## Technologies

This repository contains **`Python`** code where popular libraries such as **`Pandas`**, **`Numpy`**, **`Matplotlib`** and **`Seaborn`** are used for data analysis and visualization.

## Data processing: ETL

* Dataset import: wine_reviews
* Transformation and elimination of records that contained null information or content that was irrelevant to our analysis
* The clean data is saved to be able to carry out a correct analysis.

## Exploratory data analysis

After performing data cleaning and inspection on the Wine Reviews dataset, we utilized numerical and statistical analysis techniques to generate visualizations from the dataset.
Some of the analyses conducted: 

* All wines come with a score of at least 80.
* Price and points are not so related.
* Variety of Pinot Noir was the most frequently reviewed followed by Chardonnay and Cabernet Sauvignon.
* The majority of wine reviewed is from the France, US and Italy.
* The most expensive wine in all the reviews cost $3300 and is from France.
* The variety with the most reviews is pinot noir.

  
## Conclutions

In data analysis, it's observed that both low-priced and high-priced wines tend to receive high ratings. This trend may be attributed to the perceived value of these wines relative to their price, or possibly because consumers reserve more expensive wines for special occasions, influencing the higher ratings they receive. Consequently, wine producers may consider allocating their resources strategically to meet market preferences. Overall, there appears to be no clear correlation between price and quality when comparing most commercial wines.

#### Dataset source
 From Kaggle: https://www.kaggle.com/zynicide/wine-reviews/data
