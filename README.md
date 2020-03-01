# Hack The Burgh - VI
# Project - Trading Bot for the Optiver Challenge

The Challenge is to create a trading algorithm to make money by buy and selling stocks on two indeces : S&P500 (SP) and Eurostoxx (ESX).

Our project is composed of three parts:

1 - The trading algorithm itself  
2 - An SMS alert functionality to communicate profits and losses  
3 - A Web page for data visualization  


1 - Algorithm  
We use the Ichimoku Cloud Indicator, a fairly safe and simple strategy especially for micro trading.  
The indicator is based on four components:  
1) Conversion Line -> midpoint of the last 9 average prices  
2) Base Line -> midpoint of the last 26 average prices  
3) Leading Span A -> midpoint of Conversion Line and Base Line  
4) Leading Span B -> midpoint of the last 52 average prices  

Trading Strategy:  
The Leading Spans consitute the boundaries of the "cloud". When Leading Span A is moving above Leading Span B it indicates an uptrend is gaining momentum. Conversly, Leading Span B above means a downward trend is taking place. A thin cloud shows indecision and a potentially weakening trend.



*Trading Strategy* : Ichimoku Kinko Hyo. ... context TBD


*Team*: ... TBD

# usage instructions

## front-end
1) `cd front_end/`
2) `python -m SimpleHTTPServer`
3) go to `0.0.0.0:8000`
