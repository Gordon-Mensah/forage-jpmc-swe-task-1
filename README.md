# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program

### Stock Price Query Script

This script fetches stock data from a server, processes it to compute mid prices, and calculates the price ratio of two specific stocks.

#### License
- The script is provided under the MIT License, allowing free use, modification, and distribution with proper attribution. It is provided "as is" without warranty.

#### Features
- Fetches stock data from a server.
- Computes bid, ask, and mid prices for each stock.
- Calculates the price ratio of two specified stocks.

#### Usage
- The script makes 500 requests to a specified server URL.
- It extracts stock data, calculates mid prices, and prints the price ratio of stocks "ABC" and "DEF".

#### Key Functions
- `getDataPoint(quote)`: Processes a stock quote to extract the stock symbol, bid price, ask price, and calculates the mid price.
- `getRatio(price_a, price_b)`: Computes the ratio of two prices, handling division by zero.

#### Example Output
```
Quoted ABC at (bid:100, ask:102, price:101)
Quoted DEF at (bid:200, ask:202, price:201)
Ratio 0.5024875621890547
```
