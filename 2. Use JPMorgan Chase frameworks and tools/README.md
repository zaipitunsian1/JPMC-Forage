<h4>What are the issue?</h4>
Typically, traders monitor stock prices and trading strategies by having data displayed visually on their screens in chart form. Often
these charts will be accompanied by alerts that notify users when certain events occur or when preset price thresholds are hit.<br>
<br>
JPMorgan Chase created the Perspective tool over many years to allow users to present and manipulate data feeds visually in web
applications.<br>
<br>
Perspective provides a set of flexible data transforms, such as pivots, filters, and aggregations. It utilises bleeding-edge browser
technology such as Web Assembly and Apache Arrow and is unmatched in browser performance. It is engineered for reliability and
production-vetted on the JPMorgan Chase trading floor.

<h4>Whats the Task?</h4>
The objective of this was to fix the client-side web application so that it displays a graph that automatically updates as it
gets data from the server application (see Before and After images below).<br>
<br>
Before, the web application only gets data every time we
click on the 'Start Streaming Data' button and does not aggregate duplicated data.
<h4>Now</h4>
Now graph displayed in the client-side web application is continuously updating line graph whose y-axis
is the stock’s top_ask_price and the x-axis is the timestamp of the stock.
The continuous updates to the graph is the
result of continuous requests and responses to and from the server for the stock data.<br>
<br>
This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server.
