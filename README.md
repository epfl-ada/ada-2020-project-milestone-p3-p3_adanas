# ada-2020-project-milestone-p3-p3_adanas

## Title
Forecasting Dow Jones Index Volatility during the COVID-19 crisis.

## Abstract
The paper has shown a clear improvement in near-term forecasting performance by adding appropriate Google Trends time series as predictors, in particular during recessions. While the paper was focused on economic indicators, we would like to tackle the stock market and especially the NASDAQ index (subject to change for an individual stock). Our goal will be to to relate the index volatility to the query volume of related search terms during the COVID-19 pandemic. To do so, we will first need to find the most relevant search terms for the selected index/stock. Then, we will use an AR model with and without Trends data to forecast the index/stock volatility. Finally, we’ll try to improve this model.

## Research questions
- How can we select the most relevant search terms?
- How much does adding Trends data outperform models not using it?
- What models perform the best when it comes to forecasting stock volatility?

## Proposed datasets
- DJI Index ( [yfinance](https://pypi.org/project/yfinance/) )
- Google Trends (of course…)

## Methods
- Data collection: Extract the index/stock time series for 2020 (until end of november) from Yahoo and (naively) the related search term queries from Google Trends.
- Models: Build a simple AR model for forecasting and try different ways to improve the search terms selection and dimensionality (PCA…)
- Analysis & improvement: We will analyze our model performance according to the following metric: Does adding Trends data improve the MSE?

## Proposed timeline
- Week 1:
    - Task A: Get the Yahoo data and check it. It may need some cleaning or transformation.
    - Task B: Brainstorm ways to determine the search terms for which a change in query volume is related to a change in the concerned stock volatility.
- Week 2:
    - Task C: Fit a simple baseline model.
    - Task D: Add Trend data, compare the performance and redo task B if necessary.
- Week 3:
    - Task E: Try to improve the model (we may not have the time to complete this task).
    - Task F: Conclude, prepare the data story and film the video.

## Organization within the team
- A: Mongi extracted the Yahoo dataset while Nour listed the relevant search terms and extracted them from google Trends.
- B: Mongi and Nour will brainstorm on the search term selection improvement.
- C: Mongi developed and fitted a baseline model and a trends model.
- D: In the meantime Mongi implemented the previously brainstormed ideas from task B.
- E: Upload an html template and create repo for data story. (Everyone)
- F: Mongi finished the notebook explaining the ideas, methods, math and code.
- G: Mongi and Nour focused on writing the data story and preparing all needed figures and examples.
- H: Wrap-up and final touches. (Mongi and Nour) 

## Reference for inspiration
"Quantifying Trading Behavior in Financial Markets Using Google Trends", Tobias Preis, Helen Susannah Moat & H. Eugene Stanley, 2013

## Questions for TAs (optional)
