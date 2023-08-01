# Forecasting : Analyzing Climate Trends and Forecasting Weather in India

The purpose of this Python project is to analyze historical weather data for India from 1901 to 2017 and develop a predictive model to forecast future temperatures. The project aims to gain insights into weather patterns, identify trends in yearly temperatures,examine the potential impact of global warming on climate and give out maximimum,minimum and mean temperature also to forecast future temperature. Various data manipulation and visualization techniques, as well as the KMeans clustering algorithm and Decision Tree Regression were used to achieve it.

## Introduction
Weather forecasting plays a vital role in understanding climate trends and making informed decisions in various sectors such as agriculture, tourism, and disaster management. By analyzing historical weather data and developing a predictive model, we can gain insights into weather patterns, identify seasonal variations, and assess the impact of climate change.

![Screen Shot 2023-08-02 at 12 42 08 AM](https://github.com/prpal9122001/Analyzing-Climate-Trends-and-Forecasting-Weather-in-India/assets/72788936/fc417773-a4e2-4864-8da6-f74716aaced3)

## Methodology:

Data Collection: We obtained historical weather data for India from 1901 to 2017 in CSV format.

Data Preprocessing: We used the pandas library to preprocess the data. This involved melting the dataset, converting strings to datetime objects, and renaming columns for better readability.

Data Visualization: We used the plotly package for interactive and engaging visualizations. We created line plots to visualize yearly temperature trends, box plots to compare monthly temperatures, and scatter plots to examine seasonal variations.

KMeans Clustering: We utilized the KMeans clustering algorithm to identify potential temperature clusters and visualize them with scatter plots.

Decision Tree Regression: We implemented Decision Tree Regression to develop a predictive model for forecasting future temperatures based on historical data.

![Screen Shot 2023-08-02 at 12 26 44 AM](https://github.com/prpal9122001/Analyzing-Climate-Trends-and-Forecasting-Weather-in-India/assets/72788936/85e4a5cb-2d92-4ed3-8327-4e51e6876004)

## Insights Derived from Data Analysis

Yearly Mean Temperatures: We observed a clear positive trend in yearly mean temperatures, indicating a possible impact of global warming.

Seasonal Variability: Different seasons show distinct temperature characteristics. Winter months (January and February) exhibit the coldest temperatures, while summer months (April to September) experience the hottest temperatures. The months of March, October, and November represent moderate temperature ranges.

Global Warming Confirmation: The analysis of yearly mean temperatures confirms the issue of global warming. Since 1979, there has been a significant upward trend, especially after 2015, signifying a critical concern that needs attention.

Temperature Clusters: Despite four distinct seasons in India, we observed three main temperature clusters. These clusters represent different temperature zones experienced throughout the year.

![Screen Shot 2023-08-02 at 12 34 22 AM](https://github.com/prpal9122001/Analyzing-Climate-Trends-and-Forecasting-Weather-in-India/assets/72788936/96524763-8937-40f0-a96c-90db135e3c49)

## Machine learning algorithms used

**1.K-Means Clustering**  

K-Means is an unsupervised machine learning algorithm used for clustering data. Its main objective is to divide data into 'k' distinct clusters, where 'k' is a user-defined number. The algorithm assigns each data point to the cluster whose centroid is closest to it. K-Means is widely used in data analysis and pattern recognition tasks.

In this project, K-Means was used for the following purposes:

Seasonal Clustering: The temperature data was grouped into seasons (Winter, Summer, Monsoon, and Autumn) based on the mean temperatures of specific months. K-Means clustering helped identify distinct temperature patterns that represent each season, providing insights into the temperature variations experienced throughout the year in India.

**2.Decision Tree** 

A Decision Tree is a supervised learning algorithm used for regression and classification tasks. It creates a tree-like model where each internal node represents a feature, each branch represents a decision based on that feature, and each leaf node represents the outcome or target variable. Decision Trees are intuitive, easy to interpret, and can handle both categorical and numerical data.

In this project, Decision Tree was used for the following purposes:

Forecasting Temperature: The Decision Tree algorithm was utilized to predict the temperature for specific years. It was trained on historical temperature data from previous years, and then used to forecast the mean, maximum, and minimum temperatures for user-inputted years. This allowed for temperature predictions beyond the available historical data.

## Conclusion

In conclusion, this Python project provides valuable insights into historical weather data for India, helping us understand climate patterns and trends. By utilizing data manipulation, visualization, and machine learning techniques, we successfully developed a **predictive model to forecast future temperatures**. The analysis confirms the impact of global warming and highlights the urgency of climate action. Additionally, identifying temperature clusters allows us to study temperature variations in different regions. 






