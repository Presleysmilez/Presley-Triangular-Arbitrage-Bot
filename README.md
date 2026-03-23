# Presley-Triangular-Arbitrage-Bot
A Python-powered triangular arbitrage bot designed to identify and capitalize on price discrepancies between cryptocurrency pairs. The system integrates with exchange APIs, processes real-time market data, and executes trades algorithmically to maximize profit opportunities.


# Presley Triangular Arbitrage Bot

A Python-powered bot that finds and (potentially) executes **triangular arbitrage** opportunities in cryptocurrency markets.

Triangular arbitrage means finding price differences between **three** related pairs on the same exchange (e.g. BTC/USDT → ETH/BTC → ETH/USDT) to make risk-free(ish) profit.

**⚠️ WARNING**  
This is for **educational purposes only**. Real trading involves:
- High risk of loss (fees, slippage, latency, exchange bans)
- API rate limits & withdrawal restrictions
- Never use real money without testing thoroughly in simulation mode first!

## Features
- Connects to exchange APIs (e.g. Binance, Bybit, etc.)
- Scans for triangular opportunities in real-time
- Calculates profit after fees
- (Optional) auto-execute trades — use with caution!

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/Presleysmilez/presley-triangular-arbitrage-bot.git
   cd presley-triangular-arbitrage-bot