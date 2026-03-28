1. Methodology
 * Data Preparation: Cleaned and aligned two key datasets: Bitcoin Market Sentiment (Fear/Greed Index) and Historical Trader Data from Hyperliquid.
 * Alignment: Converted all timestamps to a daily date format and used a "left join" to map sentiment classifications to over 200,000 individual trade executions.
 * Metric Engineering: Developed key performance indicators (KPIs) including Daily PnL, Win Rate, and Average Trade Size (USD) to evaluate performance across different market moods.
2. Key Insights
 * Sentiment Impact on Profit: Analysis shows that performance is significantly higher during Extreme Greed (Avg PnL ~205) compared to Extreme Fear (Avg PnL ~1.89), indicating that traders in this dataset are better at capturing momentum than navigating crashes.
 * Behavioral Shifts: There is a clear correlation between sentiment and risk; traders increase their average position sizes and trade frequency as the market moves toward "Greed".
 * Segment Performance: Large Traders (top 50% by trade size) capture exponentially more profit during bullish phases, whereas Small Traders struggle to remain profitable during "Fear" volatility, nearly hitting a break-even PnL.
3. Actionable Strategy Recommendations
 * Rule 1 (Capitalize on Greed): During Extreme Greed, "Large" segment traders should maintain or slightly increase position sizes, as this is the environment where they generate the highest alpha.
 * Rule 2 (Risk Mitigation in Fear): During Extreme Fear, "Small" or inconsistent traders should reduce trade frequency by at least 50% or implement tighter stop-loss limits to protect capital from low-profit volatility