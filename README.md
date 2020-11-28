# CAPM for calculating the Expected Return of a Stock

## What is CAPM?
The Capital Asset Pricing Model (CAPM) is a model that describes the relationship between the expected return and risk of investing in a security. It shows that the expected return on a security is equal to the risk-free return plus a risk premium, which is based on the beta of that security. Below is an illustration of the CAPM concept.

CAPM is calculated according to the following formula:

### ER_i = R_f + β_i(ER_m − R_f)
Where,

ER_i = expected return of investment

R_f = risk-free rate

β_i = beta of the investment

ER_m = expected return of market

(ER_m - R_f) = market risk premium

### Risk-free rate
The “R_f” notation is for the risk-free rate, which is typically equal to the yield on a 10-year US government bond.  The risk-free rate should correspond to the country where the investment is being made, and the maturity of the bond should match the time horizon of the investment. Professional convention, however, is to typically use the 10-year rate no matter what, because it’s the most heavily quoted and most liquid bond.

### Beta of the investment
The beta (denoted as “B_i” in the CAPM formula) is a measure of a stock’s risk (volatility of returns) reflected by measuring the fluctuation of its price changes relative to the overall market. In other words, it is the stock’s sensitivity to market risk. If a stock is riskier than the market, it will have a beta greater than one. If a stock has a beta of less than one, the formula assumes it will reduce the risk of a portfolio.

The formula for calculating beta is the covariance of the return of an asset with the return of the benchmark, divided by the variance of the return of the benchmark over a certain period.

### Market Risk Premium
From the above components of CAPM, we can simplify the formula to reduce “expected return of the market minus the risk-free rate” to be simply the “market risk premium”.  The market risk premium represents the additional return over and above the risk-free rate, which is required to compensate investors for investing in a riskier asset class. The more volatile a market or an asset class is, the higher the market risk premium will be.

### About the Project
In this project, I have worked with Walmart (WMT) and S&P (GSPC) market index.

#### Approach
1. Calculating covariance of security returns (WMT and GSPC)
2. Calculating covariance of walmart returns with market index returns
3. Calculating variance of market index returns
4. Calculating Beta and expected return
5 Calculate the expected return of WMT using CAPM.

