# Statistical Arbitrage Cointegration Strategy

This project demonstrates a simple pair trading strategy using cointegration between two stocks. The code fetches historical stock data using the Polygon API, checks for cointegration between two portfolios, and implements a backtesting framework to evaluate the strategy.

### Images of Strategy and Performance:

#### Portfolio PnL
This graph shows the cumulative profit and loss (PnL) from the strategy. The gross PnL, long-only PnL, and short-only PnL are displayed over time, illustrating the performance of the overall strategy and its individual components.

![Portfolio PnL](https://github.com/Rah9742/statistical-arbitrage/blob/main/Images/INTU-TEAM_PnL.png)

#### Cointegration Strategy
The cointegration strategy examines the relationship between two portfolios. When the spread between them widens beyond a certain threshold, trading signals are triggered, and the strategy exploits the mean-reverting behavior of the spread.

![Cointegration Strategy](https://github.com/Rah9742/statistical-arbitrage/blob/main/Images/INTU-TEAM_Cointegration_Strategy.png)

#### Return Spread
This chart illustrates the percentage difference in returns between the two portfolios. The spread is the main driver of the strategy, and significant deviations from the mean indicate potential trading opportunities.

![Return Spread](https://github.com/Rah9742/statistical-arbitrage/blob/main/Images/INTU-TEAM_Return_Spread.png)

#### Spread
This plot shows the spread between the two portfolios over time, along with the upper and lower Bollinger Bands. When the spread crosses these bands, it signals a potential trading opportunity, where the strategy expects the spread to revert to the mean.

![Spread](https://github.com/Rah9742/statistical-arbitrage/blob/main/Images/INTU-TEAM_Spread.png)

#### Return Performance
This graph displays the cumulative return performance of the two portfolios. It tracks the return trajectories of the portfolios over time, providing a comparison of their performance.

![Return Performance](https://github.com/Rah9742/statistical-arbitrage/blob/main/Images/INTU-TEAM_Return_Performance.png)

---

The strategy leverages these insights to execute trades based on the statistical relationship between the portfolios, generating profits from mean-reverting price movements.
