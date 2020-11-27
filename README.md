# ada-2020-project-milestone-p3-p3_adanas

## Title
Quantifying related search terms impact on the NASDAQ during the COVID-19 crisis.

## Abstract
The paper has shown a clear improvement in near-term forecasting performance by adding appropriate Google Trends time series as predictors, in particular during recessions. While the paper was focused on economic indicators, we would like to tackle the stock market and especially the NASDAQ index (subject to change for an individual stock). Our goal will be to relate the index volatility to related terms query volume during the COVID-19. To do so we will first need to find the most relevant search terms for the selected index/stock. Then, we will use an AR model and log transformation (with and without Trends data) to forecast the stock’s volatility. Finally we’ll try to improve this model.

## Research Questions
- What models perform the best when it comes to forecasting stock volatility?
- Can we use the stock market data and Google Trends for january and february 2020 to predict the stock market crash of march 2020? (Hard to implement)
- How much it outperforms models not using Google Trends?
- What are the list of queries that are significant in this case?
- How can we select the most relevant search terms?
- How is Google Trends data correlated with stock volatility ?

## Proposed dataset
- Dow Jones Industrial Average (DJIA)
- S&P 500 Index
- Nasdaq Composite
- Google Trends (of course…)

All the financial datasets are available on Yahoo Finance and can be accessed using the library [yfinance](https://pypi.org/project/yfinance/).

## Methods
As done in the paper, we should first find a rather simple forecasting model for the market index price and improve it by adding appropriate Google Trends time series. First, we should have a list of keywords (queries) that are significant. Second, find the base model. Finally, improve the model and quantify the improvement in forecasting performance.

## Proposed timeline
- Task A: Get the Yahoo data and check if it needs some cleaning or transformation.
- Task B: Find a way to determine the search terms for which a change in query volume is related to a change in the index volatility.
- Task C: Fit a baseline model and an improved model.
- Task D: Compare our results and interpret them.
- Task E: Conclusion.

## Organization within the team

## Questions for TAs (optional)
- Can we use multiple time series from google trends and apply some dimension reduction (as PCA or Auto-encoders) before fitting the models?


