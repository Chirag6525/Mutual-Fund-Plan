# Mutual-Fund-Plan
A Mutual Funds Investment Bucket that is optimized for long-term investments by balancing risk and returns. This involves selecting companies that provide consistent growth and moderate returns while minimizing exposure to volatility.

- The goal is to develop a Mutual Funds Investment Bucket that is optimized for long-term investments by balancing risk and returns. This involves selecting companies that provide consistent growth and moderate returns while minimizing exposure to volatility. Specifically, the objectives are:

1. **Stock Selection**: Identify stocks with high ROI and low volatility, which will form the core of the mutual funds portfolio.
2. **Performance Evaluation**: Use metrics such as volatility (standard deviation) and expected ROI to assess which stocks are optimal for inclusion in the portfolio.
3. **Investment Strategy**: Simulate the expected future value of investments based on monthly contributions over different time horizons (e.g., 1 year, 3 years, 5 years, and 10 years).
4. **Risk-Reward Balance**: Develop a strategy that ensures a balance between risk and reward, targeting long-term investors who seek stable, compounded growth over several years.

## Dataset
The dataset consists of daily closing stock prices of 50 major Indian companies from sectors like banking, technology, consumer goods, and automotive. Each company is represented by a ticker symbol (e.g., RELIANCE.NS, ICICIBANK.NS), and the dataset includes the following features:

- **Date**: The date on which the stock price is recorded.
- **Closing Price**: The adjusted closing price for each stock on that particular date.
- **Companies**: A total of 50 top Indian companies are represented, covering a range of sectors like banking (HDFC Bank, ICICI Bank), technology (TCS, Infosys), consumer goods (Hindustan Unilever, ITC), automotive (Tata Motors, Bajaj Auto), and others.


## Analysis Report
The following companies meet the criteria of **high ROI** and **low volatility**:

1. ICICI Bank (ROI: 13.48%)
2. IndusInd Bank (ROI: 7.16%)
3. JSW Steel (ROI: 7.02%)
4. Axis Bank (ROI: 6.59%)
5. HDFC Bank (ROI: 6.32%)
6. Sun Pharma (ROI: 5.63%)
7. Kotak Bank (ROI: 5.47%)
8. Cipla (ROI: 4.85%)
9. NTPC (ROI: 4.36%)

-To balance the investment between these companies, we use an inverse volatility ratio for allocation.Companies with lower volatility will get a higher weight.

The investment ratios based on inverse volatility are as follows:

1. NTPC: 28.08%
2. JSW Steel: 15.99%
3. Axis Bank: 9.22%
4. HDFC Bank: 8.93%
5. Cipla: 8.48%
6. Kotak Bank: 7.66%
7. IndusInd Bank: 7.44%
8. Sun Pharma: 7.26%
9. ICICI Bank: 6.93%


## Expected Returns
The expected returns a person will get from our mutual fund if he/she invests **₹5000 every month.**

To calculate the expected value a person will accumulate over 1 year, 3 years, 5 years, and 10 years through the mutual fund plan, we can follow these steps:

1. Assume the person is investing 5000 rupees every month.
2. Use the expected ROI from the mutual fund companies to simulate the growth over time.
3. Compute the compounded value of the investments for each period (1y, 3y, 5y, and 10y).
4. Visualize the accumulated value over these periods.

- After 1 year, the accumulated value is around ₹62,000, and by 5 years, it grows to over ₹300,000. The long-term benefit is evident, with the investment growing to nearly ₹860,000 over 10 years, which emphasises the value of consistent investing and compounding over time for long-term investors.

## Summary

This is how a mutual fund plan is designed by investment companies for long-term investors. Mutual funds are investment plans that pool money from multiple investors to purchase a diversified portfolio of stocks, bonds, and other securities, managed by professional fund managers.