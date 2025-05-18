# Stock-Market-Analysis(Interactive dashborad using Tableau)
This project presents a stock market dashboard that analyzes historical stock data (2016–2019) for major tech companies including Apple, Facebook, Google, Nvidia, Tesla, and Twitter. The dashboard highlights key metrics such as price changes, trading volume, percentage volatility, and moving averages. It provides clear, visual insights into market trends and stock performance to support data-driven investment decisions.
# Data Used
<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/AAPL.csv">Appple_stock_data<a/>

<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/FB.csv">Facebook_stock_data<a/>

<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/GOOGL.csv">Google_stock_data<a/>

<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/NVDA.csv">Nvidia_stock_data<a/>

<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/TSLA.csv">Tesla_stock_data<a/>

<a href="https://github.com/Pushkar2520/Stock-Market-Analysis/blob/main/TWTR.csv">Twitter_stock_data<a/>

# KPIs
## A.  Time Range
### KPI: Start date and end date
- What is the time range covered in the stock market data?

## B.  Stock Price Movements
### KPI: Highest & lowest stock prices
- What was the highest stock price recorded in the period?
- What was the lowest stock price recorded in the period?
- Which company had the most significant price increase or decrease?

## C.  Daily Stock Change
### KPI: Daily price change, percent change
- What is the price change for each stock compared to the previous day?
- Which stock gained/lost the most in percentage terms today?

## D.   Volume Metrics
### KPI: Daily trading volume, total volume
- What was the total volume traded in the given time period?
- What is today’s total trading volume?
- Which stock had the highest change in volume compared to the previous day?

## E.  Price Distribution
### KPI: Histogram of price percent change
- What is the distribution of percentage price changes across all stocks?
- Are most stock price changes clustered around a certain range?

## F.   Moving Averages
### KPI: MA50 and MA100 (Moving Averages)
- How does Apple’s 50-day and 100-day moving average compare with its open price?
- Are there any crossover signals between the 50-day and 100-day moving averages?

## G.   Company-specific Metrics
### KPI: Close prices, open prices, daily volume per stock
- What is today’s closing price for each company?
- How did each company's volume change from the previous day?



# Process for Dashboard
### Data Extraction
- We start by sourcing stock market data from reliable financial APIs or CSV files. This data includes daily stock prices, trading volume, and other relevant metrics.

### Data Preparation with Pandas
- We use Pandas to manipulate our data and create new columns like the moving average and percent change, which are used for comparison in order to generate the final CSV 
files that will be used to build the dashboard.
- This step includes:
1. Parsing date fields
2. Filtering unnecessary columns
3. Handling missing values
- Calculating indicators such as 50-day and 200-day moving averages

### CSV Export
- Once processed, the data is exported into CSV format. These files serve as the input for the dashboard visualization.

### Dashboard Development
- Using a dashboarding tool Tableau I visualize the trends in the stock market using:
1. Line charts for price movements
2. Bar charts for volume
3. Indicators for moving averages and percent change

### Analysis and Insights
- The final dashboard allows users to compare stock performance over time, identify trends, and make informed decisions.
