# CODENoah Orbital MT4

Developer: Forex Robot Easy Team

Website: forexroboteasy.com

[Detailed Reviews and Trading Results](https://forexroboteasy.com/forex-robot-review/review-codenoah-orbital-mt4-a-smart-ea-for-your-forex-trading-portfolio/)

## Description

CODENoah Orbital MT4 is an Expert Advisor (EA) designed to trade forex portfolios based on a highly intelligent algorithm. The algorithm identifies profitable trading opportunities and cuts losses when trading conditions are not suitable.

This EA provides a user-friendly interface and offers customizable input parameters for trading lot size, stop loss, and take profit. Traders can adjust these parameters according to their risk appetite and trading strategy.

## Trading Strategy

The main function of CODENoah Orbital MT4 is to analyze the current market conditions and execute trading orders based on the following strategy:

1. Retrieve current market conditions, including the bid and ask prices.
2. Check if there is a chance of profit by comparing the bid and ask prices.
3. If the ask price is higher than the bid price, the algorithm determines whether to open a buy or sell order based on the difference between the ask and bid prices.
4. If the difference is greater than the specified stop loss value multiplied by the minimum price change (Point), a buy order is opened.
5. If the difference is less than the negative value of the specified stop loss multiplied by the minimum price change (Point), a sell order is opened.
6. If the market conditions are not suitable for trading (ask price is not higher than the bid price), any open orders are closed.

## Input Parameters

- LotSize: Specifies the trading lot size. Default value is 0.01.
- StopLoss: Specifies the stop loss in pips. Default value is 50.
- TakeProfit: Specifies the take profit in pips. Default value is 100.

## Functions

### OpenBuyOrder

Function to open a buy order based on the specified parameters.

### OpenSellOrder

Function to open a sell order based on the specified parameters.

### CloseOrder

Function to close an open order based on the specified ticket number.

## Disclaimer

This code sample is provided by Forex Robot Easy for demonstration purposes only. Forex Robot Easy is not the official developer of CODENoah Orbital MT4. For the official developer and more information about this product, please visit MQL5.

Please refer to the detailed reviews and trading results of CODENoah Orbital MT4 on our website: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-codenoah-orbital-mt4-a-smart-ea-for-your-forex-trading-portfolio/) for a comprehensive understanding of this product's performance.
