---
title: Monty
description: Bitcoin trading bot
date: 2017-12-24
github: https://github.com/seanlh/monty
layout: project
---

Monty is a Python 3 trading bot originally created to trade Bitcoin on various exchanges. At the moment, Monty uses real-time exchange information using the GDAX WebSockets API in order to fetch the current price of bitcoin.

It then uses this information to construct the financial technical analysis indicators. The bot uses indicators such as the Moving Average Converge Divergence (MACD) and Relative Strength Index (RSI) to gauge what position to take in the market. It takes long/buy positions when it calculates the market may be at a low, and takes short/sell positions when it thinks the market is at a high.