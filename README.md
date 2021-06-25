# Pinescript Scripts

## Donchian Ichimoku Hybrid Channel

An indicator of my own design. The Donchian channel gives concrete entries, but can't determine when price is trending vs ranging. The Ichimoku cloud can determine market state, but gives fuzzy entry and exit signals. Why not combine them?

How to interpret the indicator:
* GREEN bars are when price is trending upward
* GREEN zones are value areas in an uptrend
* RED bars are when price is trending downward
* RED zones are value areas in a downtrend
* GRAY bars are when price is ranging (going sideways)

This indicator is perfect for scalping: play the long side when the bars are green, play the short side when the bars are red, and play both sides when the bars are gray.

[Live on TradingView](https://www.tradingview.com/script/5Ow827uB-Donchian-Ichimoku-Hybrid/)

## EMA Crossover Strategy

Exponential Moving Average (EMA) Crossovers measure drift in the market. The key to a successful EMA crossover system is to have a minimum multiplier between the slow and fast averages. According to Market Wizard and hedge fund manager Ed Seykota, the slow EMA length should be at least 3x the fast EMA length. This helps the system from getting chopped up in sideways markets. The indicator enforces this multiplier.

The strategy allows historical tests on any timeframe and market. It also includes a long-only option for historically upward markets such as stocks and crypto.

[Live on TradingView](https://www.tradingview.com/script/sxJejjdy-EMA-Crossover-Strategy/)

## Generic Strategy

Before we trade, we want to be confident the strategy works on our timeframe and market. We can look to historical data to see how the strategy would've performed in the past.

We can avoid some failing strategies before we begin:
* Overactive strategies can get eaten alive by fees. We can reduce the activity of the system or trade a different market.
* Some markets don't have enough volatility to trade. Traders only make money when price moves!
* Some markets don't have enough upward movement. We can choose a better market or play solely from the short side.

To use: copy and paste the code into the Strategy tab of TradingView. Paste another indicator into the LOGIC section and change the conditions for entering and exiting.

## Turtle Trader

The turtles were a group of traders in the 80's who used a simple trend following system to overwhelming success. While the system itself is dated, the original turtle trader rules are a fantastic example of a professional trading system due to their risk management rules. The original rules give the average person a solid foundation into trading. [Search for the original turtle rules PDF](https://duckduckgo.com/?q=turtle+trader+pdf)

Features:
* Variable length channels
* Color indicators to show when in a trade long (green), short (red), and out of the market (gray)

To use: copy and paste the code into the Strategy tab of TradingView.
