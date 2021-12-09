---
title: Algorithmic Trading Backtesting
description: Algorithmic Trading Project
date: "2019-11-15T09:37:55"
publishDate: "2019-11-15T09:37:55"
---

This project was implemented to trade securities based on moving average crossovers. Looking at moving averages can indicate potential entry and exit points. While this program does not handle live data, it provides interesting results that can be useful to keep in mind for real time scenarios. 

{{< figure src="/projects/images/Candlestick.png">}}

<!--more-->

The motivation behind this project, pertains to my interest in finance, especially in technical analysis. This is the pratice of predicting future prices based on characteristics of past prices, following the belief of history tends to repeat itself. 

To predict price movements in this program moving averages were used. A moving average is the average price over a certain time interval. As the next datapoint is formed, it then replaces the old datapoint in the average creating a 'moving average'. By using a short term moving average and a long time moving average a security can be determined if it is overbought and oversold, and then act of these indicators. If the short term moving average is above the long term moving average then the security can be considered overbought, while if the opposite is true, the long term moving average is above the short term, the security is oversold.

Running this program requires the user to enter a time period along with the ticker of the security, a three to four letter code that is unique to each security. After these credentials are fulfilled the program then tests the implemented strategy with data from the time period entered, giving the return and other statistics about performance when the program has concluded running. It will also produce a price chart of the security from that time period with the moving averages plotted, showing the entrance and exit points.

[GitHub Repository](https://github.com/Thompsonn2/CS302lab1 "GitHub Repository")