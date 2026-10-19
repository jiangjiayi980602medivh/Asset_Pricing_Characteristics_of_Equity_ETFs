# Asset_Pricing_Characteristics_of_Equity_ETFs
To identify the underlying asset characteristics of different equity ETFs and understand their sources of returns and risk profiles, thereby providing a quantitative foundation for subsequent asset allocation, market timing, and ETF selection strategies.
Asset Pricing Characteristics of the Underlying Assets of Equity ETFs
I. Objective of Asset Pricing Analysis
The objective is to identify the underlying asset characteristics of different equity ETFs and understand their sources of returns and risk profiles, thereby providing a quantitative foundation for subsequent asset allocation, market timing, and ETF selection.
The asset pricing characteristics of equity ETFs can be described from the following perspectives:
1. Fundamental Profitability Characteristics
ROE (TTM) – Mean Level
We use the arithmetic mean to measure the central tendency of ROE (Return on Equity) over the trailing twelve months (TTM). ROE is a key indicator of profitability. A higher ROE generally indicates greater capital efficiency and may suggest that a company possesses a stronger competitive advantage or core competencies.
2. Valuation Characteristics
(1) PE: Price-to-Earnings Ratio
The price-to-earnings ratio (PE) measures how the market prices a company's earnings and reflects market expectations regarding its future profitability.
(2) PB: Price-to-Book Ratio
The price-to-book ratio (PB) measures the relationship between a company's market capitalization and its net assets. It provides insights into valuation levels, potential margin of safety, and industry cycles.
3. Risk and Volatility Characteristics
(1) Beta
Beta measures the sensitivity of an individual stock's returns to market movements and reflects its exposure to systematic risk.
(2) Volatility
Historical volatility measures the variability of asset returns over time and reflects the degree of market uncertainty and risk.
4. Asset Price Characteristics
(1) Closing Price
Changes in closing prices over the past three years are used to describe the price movements of the underlying assets.
(2) Alpha
Alpha represents returns in excess of the market benchmark and is used to assess the effectiveness of stock selection.
II. Data Collection and Preparation
We selected 299 equity ETFs and used an index-ranking variable to identify the industry associated with each underlying index.
We then collected daily observations over the most recent three-year period, from July 1, 2022, to July 4, 2025. Based on the variables described in Section I, we organized the corresponding data and constructed models for each variable.
Each variable was categorized into multiple groups, and each equity ETF was assigned to the appropriate category. This process established a comprehensive profile of the asset pricing characteristics of each ETF, enabling us to draw integrated qualitative conclusions.
The data were obtained using the Tonghuashun (同花顺) financial software platform.
III. Methodology
Using September 30, 2024, as the cutoff date, we divided the data into two subsets.
We selected seven indicators: volatility, closing price, alpha, beta, price-to-book ratio (PB), return on equity (ROE), and the growth rate of ROE.
For each indicator, we calculated the mean and standard deviation to evaluate its average performance and variability. The resulting statistics were consolidated into a single table.
We then applied Principal Component Analysis (PCA) to reduce the dimensionality of the data. PCA combines multiple ETF indicators into a smaller number of principal components, integrating information from individual variables into a more comprehensive representation of overall asset performance.
Based on the principal component scores, we classified all ETFs into six groups. We then analyzed the characteristics of each group and compared them with the industries associated with the underlying ETFs to identify industry-specific asset pricing patterns.
Finally, we applied the model to ETFs whose industry classifications were unknown, determining which of the six asset groups best represented their characteristics. This classification can help investors with different risk preferences make more informed investment decisions.
IV. Data Analysis
The following data package contains the functions required for the subsequent analysis. These functions will be used to process the data, perform the relevant calculations, and implement the analytical models described above.
