## Building a Tax-Efficient Portfolio

● We built a optimization-based tax-aware portfolio construction method
that adds tax liability to standard Markowitz-based portfolio construction. Our
method produces a trade list that specifies the number of shares to buy of each
asset and the number of shares to sell from each tax lot held.

● To avoid wash sales (in which some realized capital losses are disallowed), we assume that we
trade monthly, and cannot simultaneously buy and sell the same asset.
The tax-aware portfolio construction problem is not convex, but it becomes
convex when we specify, for each asset, whether we buy or sell it.

## Predicting the state of the market (IAQF)

● We developed a technique to predict (or determine) the state of the market: bear, bull, or static using the daily price
series of the Russell 3000 and prove the validity of our approach by comparing a trading strategy based on the
technique against a buy-and-hold method for the years 2018 to 2021.

● We used the Hidden Markov model and obtained a return of 212%, much more than the traditional buy and hold
strategy, which yields 70% for 2018-2021.

## A Stochastic Model for the political business cycle

● Extended the New Keynesian Phillips Curve model to the continuous-time stochastic set up with an Ornstein
Uhlenbeck process & minimized relevant expected quadratic cost by solving the corresponding
Hamilton–Jacobi–Bellman equation

● I performed the numerical analysis for the risk-neutral and risk-averse cases using MATLAB.