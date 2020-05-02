# Data visualization of financial web graph

**Bokeh** is a data visualization library in **Python** that provides high-performance interactive charts and plots. Bokeh output can be obtained in various mediums like notebook, html and server. It is possible to embed bokeh plots in Django and flask apps.

Here, I have deployed it on <a href="https://web-app-pt.herokuapp.com/" target="_blank">my website</a> using flask, it was cool right!? :world_map:

The graph which is plotted in this financial web graph is called as *candlestick chart*

A **candlestick chart** (also called Japanese candlestick chart) is a style of financial chart used to describe price movements of a security, derivative, or currency. Each "candlestick" typically shows one day, thus a one-month chart may show the 20 trading days as 20 candlesticks.

#### This is how you can read candlestick chart ->
![Read Graph1](https://www.investorsunderground.com/wp-content/uploads/2016/05/CandlestickComposition.gif) 
##### :point_up_2:	 Close is higher than the Open  
<br>![Read Graph2](https://www.investorsunderground.com/wp-content/uploads/2016/05/HowToReadCandlesticks.gif) 
##### :point_up_2:	 Open is higher than the Close

A candlestick is composed of three parts; the upper shadow, lower shadow and body. The body is colored green or red. Each candlestick represents a segmented period of time. The candlestick data summarizes the executed trades during that specific period of time. For example a 5-minute candle represents 5 minutes of trades data. There are four data points in every candlestick: the open, high, low and close. The open is the very first trade for the specific period and the close is the very last trade for the period. The open and close is considered the body of the candle. The high is the highest priced trade and low is the lowest price trade for that period.

The high is represents by a vertical line extending from the top of the body to the highest price called a shadow, tail or wick. The low of the candle is the lower shadow or tail, represented by a vertical line extending down from the body. If the close is higher than the open, then the body is colored green representing a net price gain. If the open is higher than the close, then the body is colored red as it represents a net price decline.

##### I have tried to plot the stock finance graph of Google from 2015 to current date..
##### After successful execution we get this graph: 
![Image of Graph](https://github.com/prathameshThakur/Financial-web-graph/blob/master/bokeh_plot%20.png)

Here are some steps to follow: 
- Fork this repo.
- Install all the requirements in your system:
  - pip install python
  - pip install bokeh
  - pip install flask
  - pip install pandas_datareader
- Run ```script1.py``` in your local system..

:man_technologist::wink: Have a nice day!
