# Stock Data

##  Introduction

This repository includes ready-to-go S&P 500 stock historical data. For a sample
data set, you can see it in the [data](./data) folder.

You can get all historical key metrics, including

1. Balance sheet growth
2. Balance sheet statement
3. Cash flow growth
4. Cash flow statement
5. Financial growth
6. Income growth
7. Income statement
8. Key metrics
9. Ratios
10. Prices (OHLC)
11. S&P 500 stocks list
12. S&P 500 stocks change history
13. S&P 500 company profiles

From as early as 1980 to the end of 2023 at `10 USD`. For details, please reach out to me at `zhangyue9306@gmail.com`.

## A Sneak Peek into the Columns

For example, in the key metrics data, for each of the stock it contains columns: 

1. **symbol**: The stock ticker symbol representing the company.
2. **date**: The date on which the data was recorded.
3. **calendarYear**: The year the financial data corresponds to.
4. **period**: The financial period (e.g., Q1, Q2, Q3, Q4, FY for fiscal year).
5. **revenuePerShare**: Total revenue divided by the number of outstanding shares.
6. **netIncomePerShare**: Net income (profits) divided by the number of outstanding shares.
7. **operatingCashFlowPerShare**: Cash flow from operations divided by the number of outstanding shares.
8. **freeCashFlowPerShare**: Free cash flow (operating cash flow minus capital expenditures) per share.
9. **cashPerShare**: Total cash available divided by the number of outstanding shares.
10. **bookValuePerShare**: Company's total assets minus liabilities and intangible assets, divided by the number of outstanding shares.
11. **tangibleBookValuePerShare**: Book value minus intangible assets and goodwill, divided by the number of shares.
12. **shareholdersEquityPerShare**: Total equity divided by the number of outstanding shares.
13. **interestDebtPerShare**: Total interest-bearing debt divided by the number of outstanding shares.
14. **marketCap**: The total market value of the company's outstanding shares.
15. **enterpriseValue**: Company's total value, including debt and excluding cash.
16. **peRatio**: Price-to-Earnings ratio, the ratio of the company's stock price to its earnings per share.
17. **priceToSalesRatio**: The ratio of the company's stock price to its revenue per share.
18. **pocfratio**: Price to Operating Cash Flow ratio.
19. **pfcfRatio**: Price to Free Cash Flow ratio.
20. **pbRatio**: Price-to-Book ratio, the ratio of market price to book value per share.
21. **ptbRatio**: Price-to-Tangible Book ratio, similar to P/B but uses tangible book value.
22. **evToSales**: Enterprise Value to Sales ratio.
23. **enterpriseValueOverEBITDA**: Enterprise value divided by Earnings Before Interest, Taxes, Depreciation, and Amortization.
24. **evToOperatingCashFlow**: Enterprise Value to Operating Cash Flow ratio.
25. **evToFreeCashFlow**: Enterprise Value to Free Cash Flow ratio.
26. **earningsYield**: Earnings per share divided by the stock price.
27. **freeCashFlowYield**: Free Cash Flow per share divided by the stock price.
28. **debtToEquity**: Total debt divided by total shareholders' equity.
29. **debtToAssets**: Total debt divided by total assets.
30. **netDebtToEBITDA**: Net debt divided by EBITDA.
31. **currentRatio**: Current assets divided by current liabilities.
32. **interestCoverage**: Earnings before interest and taxes (EBIT) divided by interest expense.
33. **incomeQuality**: A measure of the proportion of income coming from core business operations.
34. **dividendYield**: Annual dividends per share divided by the stock price.
35. **payoutRatio**: The proportion of earnings paid out as dividends.
36. **salesGeneralAndAdministrativeToRevenue**: SG&A expenses divided by total revenue.
37. **researchAndDdevelopementToRevenue**: R&D expenses divided by total revenue.
38. **intangiblesToTotalAssets**: Intangible assets divided by total assets.
39. **capexToOperatingCashFlow**: Capital expenditures divided by operating cash flow.
40. **capexToRevenue**: Capital expenditures divided by revenue.
41. **capexToDepreciation**: Capital expenditures divided by depreciation expenses.
42. **stockBasedCompensationToRevenue**: Stock-based compensation divided by revenue.
43. **grahamNumber**: A figure that measures a stock's fundamental value calculated using earnings per share and book value.
44. **roic**: Return on Invested Capital.
45. **returnOnTangibleAssets**: Net income divided by tangible assets.
46. **grahamNetNet**: A value investing formula that compares stock price to net current asset value.
47. **workingCapital**: Current assets minus current liabilities.
48. **tangibleAssetValue**: The total value of physical, non-abstract assets.
49. **netCurrentAssetValue**: Current assets minus current liabilities and long-term debt.
50. **investedCapital**: Total capital invested by shareholders and debt holders.
51. **averageReceivables**: Average accounts receivable over a period.
52. **averagePayables**: Average accounts payable over a period.
53. **averageInventory**: Average value of inventory over a period.
54. **daysSalesOutstanding**: Average number of days to collect payment after a sale.
55. **daysPayablesOutstanding**: Average number of days a company takes to pay its invoices.
56. **daysOfInventoryOnHand**: Average number of days a company holds inventory before selling it.
57. **receivablesTurnover**: Sales divided by average accounts receivable.
58. **payablesTurnover**: Cost of goods sold divided by average accounts payable.
59. **inventoryTurnover**: Cost of goods sold divided by average inventory.
60. **roe**: Return on Equity, net income divided by shareholders' equity.
61. **capexPerShare**: Capital expenditures divided by the number of outstanding shares.
62. **GICS Sector**: Global Industry Classification Standard sector classification.
63. **GICS Sub-Industry**: Global Industry Classification Standard sub-industry classification.


## Usage

With the extensive range of historical financial data you've collected, 
from balance sheets to S&P 500 company profiles spanning from 1980 to 2023, 
there are numerous analytical and research opportunities. Here are some potential uses for this data:

1. **Stock Performance Analysis**:
   - Analyze long-term performance trends of individual stocks or the S&P 500 as a whole.
   - Identify patterns and correlations between stock prices and specific financial metrics.

2. **Fundamental Analysis for Investment**:
   - Use key metrics and financial statements for fundamental analysis to assess the intrinsic value of stocks.
   - Compare P/E, P/B ratios, and other financial ratios to industry averages for investment decisions.

3. **Algorithmic Trading Strategies**:
   - Develop and backtest algorithmic trading strategies using historical price data (OHLC).
   - Test strategies for different market conditions and time periods.

4. **Market Trend Analysis**:
   - Analyze trends and changes in the overall market using the S&P 500 stocks list and change history.
   - Study market cycles, bull and bear markets, and their impacts on various sectors.

5. **Corporate Financial Health Assessment**:
   - Assess the financial health and growth of companies through balance sheet, income statement, and cash flow data.
   - Identify companies with strong financials for potential investment.

6. **Sector Analysis**:
   - Segment the S&P 500 stocks by sector and perform sector-specific analyses.
   - Compare sector performance over time and identify leading and lagging sectors.

7. **Predictive Modeling and Forecasting**:
   - Use historical data to build predictive models for forecasting stock prices or market movements.
   - Apply machine learning techniques to predict trends based on financial growth and income growth metrics.

8. **Risk Management and Diversification**:
   - Analyze historical data to understand risk factors associated with different stocks and sectors.
   - Develop a diversified portfolio strategy based on historical performance and risk profiles.

9. **Economic Research and Analysis**:
   - Use the data to conduct broader economic research, such as the relationship between market performance and economic indicators.
   - Study the impact of major economic events on the stock market.

10. **Educational and Training Purposes**:
    - Utilize the dataset for educational purposes, such as teaching financial analysis, investment strategies, or econometrics.
    - Create case studies and practical exercises for finance students or trainees.

This data offers a wealth of opportunities for analysis, 
not just for making informed investment decisions, 
but also for academic research, developing financial models, 
and understanding market dynamics over a significant historical period.
