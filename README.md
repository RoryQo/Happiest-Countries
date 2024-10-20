# Project: Analysis of the Happiest Countries 

## Table of Contents 
1. [Overview](#overview)
2. [Results](#results)
3. [Data](#data)
4. [Setup](#setup)
5. [Analysis Steps](#analysis-steps)
6. [Conclusion](#conclusion)
7. [List of Happiest Countries](#list-of-happiest-countries)

## Overview
This project investigates the factors contributing to happiness across countries, utilizing the 2018 World Happiness Report dataset. We perform Principal Component Analysis (PCA) to uncover the underlying structure of happiness-related variables and apply clustering techniques to identify groups of countries with similar happiness profiles.

## Results
Through our analysis, we found that the data exhibited high correlations among variables, prompting the use of PCA. The optimal number of clusters determined was three. Interestingly, our findings revealed that the Partitioning Around Medoids (PAM) clustering method yielded nearly identical results to k-means clustering, with only two discrepancies among over 150 countries.
 
After clustering, we visualized key contributing factors such as GDP per capita and social support. The results indicated that Cluster 1, which contains the happiest countries, consistently outperformed the other clusters in these metrics. This cluster comprises 25 countries, which are listed at the end of this document.

## Data
The dataset used is the World Happiness Report from 2018, which surveys the state of global happiness based on various factors. Key variables include:

- **Overall Rank:** Numeric happiness rank (1 to 156).
- **Country or Region:** The name of the country or region.
- **Score:** A measure of subjective well-being (0 to 10).
- **GDP per Capita:** A measure of economic performance.
- **Social Support:** The national average of binary responses regarding social support.
- **Healthy Life Expectancy:** The average number of years a person is expected to live in good health.
- **Freedom to Make Life Choices:** Satisfaction with freedom in life choices.
- **Generosity:** The residual from regressing charitable donations on GDP per capita.
- **Perceptions of Corruption:** Survey responses regarding corruption in government and businesses.

## Setup
To begin, load the necessary libraries and import the dataset.

## Analysis Steps
1. **Data Preparation:** Clean the dataset by removing irrelevant columns and handling missing values.
2. **Exploratory Data Analysis:** Visualize correlations among key variables.
3. **Principal Component Analysis (PCA):** Perform PCA to reduce dimensionality and identify key contributors to happiness.
4. **Clustering:** Apply k-means and PAM clustering methods to segment countries into distinct clusters based on PCA results.
5. **Visualization:** Create plots to illustrate the relationships between clusters and happiness metrics.

## Conclusion
This analysis demonstrates the effectiveness of PCA and clustering in identifying the happiest countries and their associated characteristics. The insights gained reveal that economic and social factors significantly contribute to overall happiness. A complete list of the happiest countries in Cluster 1 can be found in the final section of this document.

## List of Happiest Countries
A full list of the countries classified in Cluster 1 can be displayed at the end of your analysis code.
