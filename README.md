# ada-2020-project-milestone-p3-p3_adanas

## Title
Quantifying trading behavior for near-term crisis prediction.

## Abstract
The paper shows a clear improvement in near-term forecasting performance by adding appropriate Google Trends time series as predictors. In particular, as seen in the replicated figure 2, they highly outperform regular models during recessions. This suggests that quantifying traders psychology, specifically fear, using Google Trends may improve predicting the close future financial crisis. This seems interesting since we just witnessed the covid-19 crisis in march 2020. This field of research is known as behavioral finance.

## Research Questions
- Can we use the stock market data and Google Trends for january and february 2020 to predict the stock market crash of march 2020?
- How much it outperforms models not using Google Trends?
- What are the list of queries that are significant in this case? 

## Proposed dataset
- Dow Jones Industrial Average (DJIA)
- S&P 500 Index
- Nasdaq Composite
- Google Trends (of course…)

All the financial datasets are available on Yahoo Finance and can be accessed using the library [yfinance](https://pypi.org/project/yfinance/).

## Methods
As done in the paper, we should first find a rather simple forecasting model for the market index price and improve it by adding appropriate Google Trends time series. First, we should have a list of keywords (queries) that are significant. Second, find the base model. Finally, improve the model and quantify the improvement in forecasting performance.

## Proposed timeline
- Task A: Get the data and check it (It may need some cleaning or tranformation)
- Task B: Fit a baseline model and an improved model
- Task C: Compare our results and interpret them
- Task D: Conclusion

## Organization within the team
- 
- 

## Questions for TAs (optional)
- Can we use multiple time series from google trends and apply some dimension reduction (as PCA or Auto-encoders) before fitting the models?


