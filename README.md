# This is my first project about quantitative finance and it's aimed to understand investment strategies and algorithmic trading. It consists of 3 parts.
&nbsp;
## I - Creating equally weighted but not market cap weighted S&P 500
I think there is no need to tell you more, everything in the name   ->   __equal_S&P500.ipynb__
## II - Quantitative Momentum Investment Strategy

Strategy that relies on systematic, data-driven approaches to identify and capitalize on stocks or assets exhibiting strong recent performance or momentum. Unlike traditional fundamental analysis, which focuses on a company's financial health and intrinsic value, quantitative momentum investing emphasizes the statistical patterns of recent price movements and other relevant metrics.

Here I used several price returns metrics to gauge the performance of assets over different time horizons and then took mean from them, sorted by top 50 and kept these as an investment "recommendation". 

## III - Quantitative Value Investment Strategy
This approach relies to identifying undervalued companies. 
&nbsp;
&nbsp;
Metrics which were used in this strategy:
1. Price to Earnings Ratio (P/E Ratio):

Description: The P/E ratio is a valuation metric that compares a company's current share price to its earnings per share (EPS). It indicates how much investors are willing to pay for each dollar of earnings.
Specifics: A higher P/E ratio may suggest that investors have high expectations for future earnings growth, while a lower P/E ratio may indicate lower expectations.
Disadvantage: The P/E ratio can be influenced by non-recurring items, accounting changes, or fluctuations in earnings. It may not capture the full picture of a company's financial health.
2. Price to Book Ratio (P/B Ratio):

Description: The P/B ratio compares a company's market value (share price) to its book value (net asset value per share), reflecting the relationship between the stock's market value and its accounting value.
Specifics: A P/B ratio below 1 may suggest that the stock is undervalued in relation to its book value, while a ratio above 1 may indicate potential overvaluation.
Disadvantage: Book value may not accurately represent the market value of certain types of assets. Additionally, the P/B ratio may not account for intangible assets, and it may be less applicable for companies with significant intellectual property or brand value.
3. Price to Sales Ratio (P/S Ratio):

Description: The P/S ratio compares a company's market capitalization to its total revenue. It measures the market's valuation of each dollar of the company's sales.
Specifics: A lower P/S ratio may indicate that the stock is undervalued relative to its sales, while a higher ratio may suggest potential overvaluation.
Disadvantage: The P/S ratio does not account for profit margins, and it may not consider the overall profitability of a company. It may also be less meaningful for companies with low revenue but high profit margins.
4. EV/EBITDA (Enterprise Value to Earnings Before Interest, Taxes, Depreciation, and Amortization):

Description: EV/EBITDA is a valuation metric that compares a company's enterprise value (market value plus debt, preferred stock, and minority interest) to its EBITDA. It assesses the company's overall value relative to its operating performance.
Specifics: A lower EV/EBITDA ratio may suggest that the company is undervalued, while a higher ratio may indicate potential overvaluation. Commonly used in M&A and valuation analysis.
Disadvantage: EV/EBITDA may not fully account for a company's capital structure or the quality of its earnings. It can also be sensitive to changes in EBITDA, and it may not be suitable for companies with high levels of debt.
5. EV/GP (Enterprise Value to Gross Profit):

Description: EV/GP is a valuation metric that compares a company's enterprise value to its gross profit. It provides insights into the company's overall value in relation to its gross profitability.
Specifics: Similar to EV/EBITDA, a lower EV/GP ratio may suggest undervaluation, while a higher ratio may indicate potential overvaluation. It focuses on the gross profitability of the company.
Disadvantage: EV/GP does not consider operating expenses, taxes, or interest. It may not provide a complete picture of a company's profitability and may be less relevant for companies with varying profit margins.


 _P.s This project is an educational endeavor created based on the guidelines provided in this [youtube video](https://youtu.be/xfzGZB4HhEE?si=WUcICx4l5Un33E1w)._