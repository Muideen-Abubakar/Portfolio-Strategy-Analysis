# Portfolio-Strategy-Analysis
When the press discusses the merits or the perils of a 60/40 portfolio; when a financial advisor refers to a Balanced Fund; when your corporate pension fund has a default fund option that is actively managed by an asset manager against a customised 60/40 benchmark:
What do these actually mean; how are they managed; and how are the performance and risk figures calculated
The ratio 60/40 is a shorthand for 60% invested in a well-diversified equity investment vehicle and the rest (40%) of the capital is invested in a comparably well-diversified fixed income instrument. They are often assumed to be re-balanced each month back to 60/40, removing any drift that might have occurred intra-month; hence a “rule-based and long-only portfolio”

The following steps/questions will be taken/answered:
1. Download month-end closing-price time-series data for the following indices, starting at 30/Sept/2003. 
- Fixed income part: iShares Core US Aggregate Bond ETF (AGG)
- Equity part: S&P 500 Index (S&P)

2. Create a return index time-series of 60% S&P + 40% AGG, rebalanced monthly. Base it at $100 on 30/Sept/2003

3. Calculate the annualised return and volatility of three portfolios, i.e. AGG, S&P, and 60/40, and return correlations between AGG and S&P in the following way
- First half of the sample and second half of the sample
- Entire sample period

4. Create monthly return distributions of AGG, S&P, and 60/40 portfolios from the entire sample and compare their statistical properties

5. If we had invested $100 in each portfolio, i.e. AGG, S&P, and 60/40, on 30/Sept/2003 and held till 31 Dec 2021, what would have been the largest loss experienced from each investment (i.e. maximum drawdown, aka MDD) and how long would they have taken to recover back to the peak of the assets prior to the MDD (i.e. recovery time back to high watermark)?

6. If we had invested $100 in 60/40 on 30/Sept/2003 and left the investment untouched without rebalancing it back to 60/40, what would be the investment outcome and how does this compare with the monthly rebalanced 60/40 portfolio as seen above?

NB: Assume no transaction costs, no liquidity concerns and no fractional investment restrictions throughout
