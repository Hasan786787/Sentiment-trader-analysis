# Sentiment-Driven Trader Behavior Analysis
Regime-Aware Segmentation & Strategy Design

Overview
This project analyzes how market sentiment (Fear vs Greed) influences trader-level profitability, volatility, and behavioral patterns.
We identify structural trader archetypes and design regime-aware capital allocation rules based on empirical findings.

Methodology
1. Data Processing
   Aggregated trader-level metrics:
      Trade frequency
      Average trade size
      Closed PnL
      PnL volatility
      Long ratio

2. Behavioral Clustering
      Standardized features
      Applied K-Means clustering
      Identified three trader archetypes

3. Regime Analysis
   Merged sentiment regime (Fear vs Greed)  
   Compared:
       Mean PnL
       Volatility expansion
       Regime sensitivity by cluster

4. Strategy Framework
       Designed regime-aware allocation rules
       Prioritized risk-adjusted stability over absolute returns

   
Key Insights:-

Trader heterogeneity is driven primarily by frequency and position sizing.
Directional bias does not differentiate trader types. 
Risk-adjusted efficiency declines with leverage intensity.
Fear regimes reward disciplined traders.
Greed regimes amplify volatility for high-exposure traders.


Strategy Recommendations:-

Increase allocation to disciplined traders during Fear regimes.
Impose leverage caps during Greed regimes.
Allocate capital based on risk-adjusted efficiency rather than raw PnL
