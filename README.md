# Predict-Annual-Returns-Societe-Genarale
Predict the portfolio’s annual returns.

### Problem Statement:
Societe Generale (SocGen) is a French multinational banking and financial services company. With over 1,54,000 employees, based in 76 countries, they handle over 32 million clients throughout the world on a daily basis.

They provide services like retail banking, corporate and investment banking, asset management, portfolio management, insurance and other financial services.

SocGen intelligence to predict, act and maximise their portfolio returns. Think of a portfolio as a basket. The basket can contain diverse instruments such as equity stocks, debentures, mutual funds etc. Each portfolio is allotted to portfolio managers. Intelligence about future performance would help these portfolio managers to act and take necessary steps in order to overcome losses.

In this problem, given the randomly sampled data, you’ve to predict the portfolio’s annual returns. Keeping data privacy in mind, some of the variables have been anonymised.

### Approach

### Feature engineering:
* OHE of some categorical features.
* Date time features as day, month, year of sell, buy.
* Difference of amounts and days of bought and sell
* Interaction features of libor rate and euribor rate.
* Interaction features of sold and bought amount.
* Mean returns per year, currency, month

### Algorithm:
Trained a xgboost model split on country wise.

### Libraries:
* Sklearn
* Pandas
* matplotlib
