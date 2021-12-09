---
title: Automated Bot Trading
description: MACD Bot Trading
date: "2020-05-20T19:49:05"
publishDate: "2020-05-02T19:49:05"
---

When looking at a stock chart with the Moving Average Convergence and Divergence technical indicator a clear pattern can be seen when looking at the cross-over points. This indicator compares a long and short term moving average to its previous points.

{{< figure src="/projects/images/MACD.png">}}

<!--more-->

The moving average convergence and divergence technical indicator uses 26 and 12 day moving averages to predict momentum in teh security being analyzed, will the price swing upward or downward. It forms two lines one that tracks the difference between the moving averages and relates that to the previous values being formed. By looking at the two cross-over points entry and exit signals can be identified.

To construct this program the python programming language was used as it offers many tools to assist in the gathering and handling of time series data making implementation much simpler. These tools include Pandas, Beautiful Soup, Alpaca, and Numpy. 

[GitHub Repository](https://github.com/Thompsonn2/ProjectLombax "GitHub Repository");