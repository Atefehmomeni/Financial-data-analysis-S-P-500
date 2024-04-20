# S-P-500-Analysis

## Overview

In this repository, we dive into the dynamic world of the stock market, analyzing the S&P 500, a leading indicator of U.S. equities. By leveraging machine learning techniques, specifically linear regression models, we aim to predict the closing stock prices and draw meaningful insights from historical data patterns.

![S&P 500 Analysis](images/sp500-banner.png)

## Dataset Description

The dataset is a treasure trove of information, encapsulating the ebb and flow of the stock market over a span of five years. Here's what each column represents:

- **Date**: Chronicles the trading days, turning the calendar into a financial timeline.
- **Open**: The day's financial curtain raise, where the opening price sets the stage for the trading day ahead.
- **High**: The peak of the market's daily mountain, marking the highest price point reached.
- **Low**: The valley of the daily trading landscape, capturing the day's lowest price dip.
- **Close**: The final act of the trading day, where the closing price brings closure to the market's daily saga.
- **Volume**: A count of the market's heartbeat, quantifying how many shares changed hands throughout the day.
- **Name**: The stock's signature, its ticker symbol, an alphabetic dance that spells out its market identity.


## Analysis Workflow

- **Data Exploration**: Investigated the dataset's characteristics and established the datetime index for time series analysis.
- **Data Cleaning**: Identified and filled missing values, and dropped irrelevant columns to refine the dataset.
- **Model Development**: Trained and evaluated three linear regression models — Simple Linear, Ridge, and Lasso Regression.

## Results

Each model was assessed using R^2 score and Mean Squared Error (MSE), with the Simple Linear Regression model showing the best performance. Detailed results and insights are documented in the project report.

## Insights

- High R^2 scores indicate strong predictive capability across all models.
- The elimination of outliers and the absence of patterns in the residual plots suggest well-fitted models.

## Conclusion

The analysis highlights the effectiveness of linear regression models in stock price prediction, with an emphasis on simplicity and interpretability for financial decision-making.
## Future Work

- Integrate additional features to assess their impact on model performance.
- Explore advanced modeling techniques, including time series analysis and ensemble methods.
## Usage

Detailed instructions on how to run the analysis are included in the `data_analysis.ipynb` Jupyter notebook. 

## Contributing

Interested in contributing? Please read through the `CONTRIBUTING.md` guidelines.

## License

This project is open-source and available under the MIT License.

---

Your feedback and contributions are welcome!
