# BTCHolders
Tracking accumulation behavior across the 100 richest Bitcoin addresses using on-chain analysis.

The query identifies how many of the top 100 Bitcoin holders have not engaged in purchasing activity in the past 7 days, providing insights into holder behavior and market stability.

Key Patterns as of April 18, 2025
1. Exchange Wallets Are Stacking
Binance, Bitfinex, Kraken, OKEx, BitMex, and Crypto.com are actively increasing cold storage holdings. This suggests:
  Growing user deposits
  Institutional inflows
  Long-term BTC storage strategies

2. Tether Resumes Accumulation
Tether's wallet shows activity for the first time in four months, potentially to:
  Rebalance USDT reserves
  Hedge against macro instability

3. Emerging Whales
Multiple unknown wallets (especially ranks #30, #46, #48, #50) are:
  Recently created
  Accumulating BTC in large amounts
  Possibly representing hedge funds, OTC desks, or sovereign entities

Implications: 
  Accumulation from whales + low retail sell pressure = supply shock potential
  Institutional Repositioning
  Cold wallet growth from exchanges suggests long-term plays

These institutions may be preparing for regulatory clarity, ETF inflows, or geopolitical hedging

This analysis is preliminary and likely will direct my attention to the following work: 
1. Wallet Clustering
  Use address clustering heuristics to link unknown wallets
  Identify common inputs, coinjoin history, or shared withdrawal sources

2. Dormant Wallet Reawakening
  Build Python script to flag wallets that activate after >6 months dormancy

3. Exchange Outflow Correlation
  Compare exchange hot wallet outflows to top 100 cold wallet growth

4. Daily/Weekly Whale Tracking Tool
  Open-source tool to track accumulation and distribute weekly reports
