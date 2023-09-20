# regression
 
Forecasting Store Sales for Corporation Favourita in Ecuador
Introduction
In a constantly evolving world of grocery retail where consumer inclination and trends in the market space keep evolving, accurate predictive sales are key factors in the success of this sector.
Being able to do predictions and meet customer demands for Favorita Corporation, a leading grocery retailer in Ecudor will not only give it a competitive advantage but also enable its sustainable growth and profitability.
In this article we embark on an extensive survey of sales forecasting that is unique to Corporation Favorita.
We intend to explore methodologies, objectives, tools, and strategies that can enhance Favorita to adopt to the emerging market dynamics hence make data-driven decisions that pilot its success.
Project Structure
Project title and introduction
Here we give the title and a summary about the project in our introduction.
Project planning and initiation
A working environment is created, and all the necessary libraries are imported.
Data collection and preparation
Data sets from various sources are collected and prepared for analysis. For this project, we will work datasets that reside in three places:
Database, OneDrive, and GitHub
Exploratory Data Analysis (EDA)
EDA helps in gaining insights, patterns identification, and make informed decisions about data analysis and modeling. Some of the steps include:
Data summary and overview
Handling missing values
Data visualization
Data distribution analysis, etc.


Data Modelling and Analysis
We select different models, train, and evaluate them based on the evaluation metrics.
Results and Findings
Best performing models are selected and recommendations made thereafter. 

Technical content
Data collection and Processing
To begin with, we collected historical sales data from Corporation Favorita's stores. We then processed our data by handling missing values, outliers, and ensuring data consistency.

The team opted for interpolation technique to estimate missing data points within a time-ordered sequence because the Interpolation method (date) considers the temporal order of observations, ensuring that the interpolated values make sense in the context of date the price was recorded. Also, trends and patterns in the data (price) are preserved, helping to maintain the integrity of the oil price data.
Additionally, exploratory data analysis (EDA) provided initial insights into the dataset. We extensively explored all our datasets to get a clear picture of datasets that we will be working with, this includes their data types, how they correlate with each other and so on.
Time Series Analysis
•	Understanding Time Series Data: 
The analysis of total sales based on different groupings reveals interesting insights into the performance of stores in various categories. 

City Analysis: Among the cities, Quito stands out with significantly higher total sales compared to other cities, indicating that it is the top-performing city in terms of sales. Guayaquil follows with a substantial but lower total sales figure. This suggests that Quito and Guayaquil are key revenue-generating cities for the stores.

Cluster Analysis: When examining sales by cluster, Cluster 14 emerges as the leader with the highest total sales, demonstrating that it is the most successful cluster in terms of revenue. Clusters 6, 8, 11, and 10 also perform well but at a slightly lower level. This analysis highlights the variation in sales performance across different clusters, with Cluster 14 notably leading the way.

State Analysis: In terms of states, Pichincha exhibits the highest total sales, significantly surpassing other states. Guayas follows with a substantial but lower sales figure. This suggests that stores located in Pichincha and Guayas contribute significantly to the overall sales, reflecting the regional variations in sales performance.

Store Type Analysis: Among the store types, Holiday stores lead in total sales, indicating that they generate the highest revenue. Event and Additional store types also perform well but at a lower level. This analysis underscores the impact of store type on sales, with Holiday stores significantly outperforming others in terms of revenue generation.

In conclusion, this analysis can guide strategic decision-making for store management, helping them focus resources and efforts on high-performing groups to further enhance sales and overall profitability.

•	Visualization Techniques: 
We used different visualization techniques to identify patterns and trends as listed below.
Box plot to visualize distribution of sales of different families
 

A histogram to visualize Count of stores by state
 

A subplot to Comparing trend of oil price and trend of sales
 

A bar plot to visualize top 5 average sales and the promotion done the sales
 

•	Stationarity: 
STATISTICAL TEST FOR STATIONARITY USING THE AUGMENTED DICKEY-FULLER (ADF) TEST AND KPSS
The Augmented Dickey-Fuller (ADF) test is commonly used to test for a unit root in a time series. The presence of a unit root is indicative of non-stationarity. To test for stationarity using the ADF test, we are checking if the time series data is stationary or non-stationary.

The null hypothesis (H0) of the ADF test is that the time series has a unit root, indicating non-stationarity.

The alternative hypothesis (H1) is that the time series does not have a unit root, indicating stationarity.

The Kwiatkowski-Phillips-Schmidt-Shin (KPSS) test is commonly employed to assess the stationarity of a time series. Stationarity implies that the statistical properties of a time series, such as its mean and variance, remain constant over time. Conversely, non-stationary time series exhibit changing statistical properties.

Null Hypothesis (H0): The null hypothesis of the KPSS test is that the time series is stationary around a deterministic trend, indicating the presence of stationarity.

Alternative Hypothesis (H1): The alternative hypothesis of the KPSS test is that the time series is not stationary, suggesting the presence of a unit root or non-stationarity.


4. Model Selection
Choosing the appropriate time series forecasting model is critical. We explored several models:
 Auto Regressive model.
 

Sarima Model
 

Arima
 
5. Forecasting
Implementing the selected forecasting model(s) on Favorita's sales data, generating forecasts for various time horizons (e.g., daily, weekly, monthly). Evaluation metrics, such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), were used to assess forecast accuracy.
8. Reporting and Visualization
We used Power BI interactive dashboards and reports to communicate sales forecasts, visualize sales trends, and highlight forecasting performance. These reports serve as valuable tools for decision-makers within Corporation Favorita.
 
Conclusion and Recommendations
The statistical analysis performed indicates that there is a significant difference in sales before and after the earthquake. The p-value, which is extremely close to zero, provides convincing evidence to support this conclusion, which is that the earthquake had a significant impact on supermarket sales.

Based on these observations and the statistical analysis, we can conclude that the earthquake had a significant and not a lasting impact on supermarket sales. The sales data show a clear disruption and a change in the trend, with higher sales levels persisting over a few months after the earthquake. 

This conclusion is supported by both visual evidence from the line graph and the highly significant p-value from the statistical test.

References
https://cloud-school.thinkific.com/courses/take/ds-career-accelerator-lp3-regression-project
https://datatab.net/statistics-calculator/regression?example=linear_regression

Appreciation
I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about Azubi Africa here and take a few minutes to visit this link to learn more about Azubi Africa life changing programs.
Tags
Azubi Data Science
https://github.com/lauranyangasi/regression
https://app.powerbi.com/groups/me/reports/3f08c729-19f7-4cc2-9cae-741cf5919d5c/ReportSection?experience=power-bi



