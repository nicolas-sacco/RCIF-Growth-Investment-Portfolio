# RCIF-Growth-Investment-Portfolio
Rational Capital Investment Fund simulated growth investment portfolio construction; analyzing KPI's and KRI's relative to equity market benchmarks. Utilized python and relevant data structure/data collection py libraries for overall model development.

# **RCIF Growth Investment Portfolio**


##Objective: Assess Key performance and risk indicators (**KPI & KRI**) for a Value Investing Portfolio; quantifying the "growth" of a company with its financial growth vectors and profitabilty metrics


##Steps:

1. Get Data for High Market Capitalization Equities in the Retail, Electronic Technology and Finance Sectors. Equities sourced from TSX and NYSE
2.Clean, normalize, and store data of the equities in a pandas dataframe

3. Identify 5-Year Dividend CAGR and Current EPS
4. Develop Algorithm: Filter for **25% 5-year Dividend CAGR** and **EPS>4.0**
5. Assess KRI's and KPI's of Portfolio: Weigh Beta and Visualize Total and Annualized Return of Portfolio in comparisson to chosen market benchmark; SPY 


### **Explanation of Growth Investing**

Investment strategy that focuses on selecting equities expected to grow at an above-average rate compared to other companies or the market as a whole. For "growth stocks" , we seek out companies that demonstrate strong potential for future growth in earnings, revenues, and other key financial metrics, often driven by innovative products/services or expanding markets. This strategy involves a long-term perspective, as it may take time for a company's growth potential to be fully realized and reflected in its stock price, thus why we are using 2019-2024 timeframe. However, growth investing can also entail higher risk compared to other investment strategies, as growth stocks are more susceptible to market fluctuations. To minimize risk of our portfolio we are going to use the quantitative **KRI: Beta β** to minimze portfolio drawdowns and overall risk by efficiently weighting our beta relative to the Standard & Poors 500 Index Fund.


### *** *KRI*:** **Beta(β)**- A measure of volatility in an equity relative to to the volatilty of the overall market
### ***KPI*: Annualized Total Return-**Average amount of capital gains realized by an investment each year over a given time period
