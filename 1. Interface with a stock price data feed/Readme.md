
<h4>Whats the task?</h4>
The trader would like to monitor two historically correlated stocks and be able to visualise when the correlation between
the two weakens(i.e. one stock moves proportionally more than the historical correlation would imply).<br>

So, we have to fix the broken client datafeed script in the repository by making the required adjustments to it.<br>


<h4>Exact purpose</h4>
We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.<br>

<h4>Acceptance Criteria</h4>
*  getDataPoint function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average
of bid and ask.<br>
*  getRatio function should return the ratio of the two stock prices.<br>
*  main function should output correct stock info, prices and ratio.<br>
