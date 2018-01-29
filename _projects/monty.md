---
title: Monty
description: Bitcoin trading bot
date: 2017-12-24
is_project: true
github: https://github.com/seanlh/monty
layout: post
---

Monty is a Python 3 trading bot. Monty currently uses the GDAX WebSockets API in order to fetch real-time price data of the BTC/USD trading pair.

It then uses this price data in order to construct the market data used in the financial technical analysis algorithms. Monty can use indicators such as the Moving Average Convergence Divergence (MACD) and Relative Strength Index (RSI) to determine how to trade.

The trading algorithm is developed in its own module, allowing the program to "plug and play" various strategies. Trading algorithms may use certain indicators to determine whether to enter the market or exit the market.