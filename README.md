# quant-pair-trade-long-only-bang
This project implements a long-only pair trading strategy on Indonesian banking stocks using cointegration and a Kalman Filter.
📊 Performance Metrics & Interpretation

The strategy performance is evaluated using multiple metrics to provide a balanced view of both profitability and risk.

Total Return measures the overall profitability of the strategy over the backtest period. While the strategy can generate positive returns, performance is driven by relative mispricing rather than market direction.

Sharpe Ratio evaluates risk-adjusted returns. The Sharpe ratio is relatively modest due to the long-only constraint, discrete mean-reversion entries, transaction costs, and residual market exposure, which introduce return volatility. This indicates opportunities for further risk optimization rather than a lack of statistical edge.

Maximum Drawdown captures the largest peak-to-trough decline in portfolio value. As a mean-reversion strategy, drawdowns may occur before price convergence, which is expected in long-only implementations.

Win Rate reflects the proportion of profitable trades. A moderate win rate is typical for mean-reversion strategies, where small frequent gains can be offset by occasional larger losses.

Profit Factor measures the ratio of gross profits to gross losses. A value above 1 indicates the presence of a positive trading edge, even if returns are uneven over time.

Together, these metrics ensure that the strategy is evaluated beyond raw returns and reflect realistic execution and risk considerations in the Indonesian market.
