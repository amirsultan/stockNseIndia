# stockNseIndia

Pulling stock data from NSE (National Stock Exchange) in India to do analytics.


Step 1: Understanding about the library NSEpy:

NSEpy is a library to extract historical and realtime data from NSE's website. This Library aims to keep the API very simple.
You can read this in more detail about the function on the below reference.
Reference: https://nsepy.xyz/
For our extraction of historical data we will use:
from nsepy import get_history (We will use get_history to extract historical data)

Step 2: Understanding of dataframe

It is necessary to understand the dataframe while writing code with python, If you have an understanding about it, you can directly skip to the next section.
Going by the definition from the official reference:
DataFrame. DataFrame is a 2-dimensional labeled data structure with columns of potentially different types. You can think of it like a spreadsheet or SQL table, or a dict of Series objects. It is generally the most commonly used pandas object.
You can go to the below reference and read more about the dataframes. Dataframe is a powerful data structure and you can't ignore it if you are working in python coding.
Reference:
https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html

Step 3: List of stocks to be extracted

To make the initial code simple, you may go and download stock codes from the NSE India websites and directly use them in the array. This will avoid further complexity. You may optimize your code later and start referencing it directly once you have a grasp on how this works.
Here, I am using the below list and added 50 stock code in NSE50 data.
nse_list = ['ADANIPORTS','ASIANPAINT','AXISBANK','BAJAJ-AUTO','BAJFINANCE','BAJAJFINSV','BHARTIARTL','INFRATEL','BPCL','BRITANNIA','CIPLA','COALINDIA','DRREDDY','EICHERMOT','GAIL','GRASIM','HCLTECH','HDFC','HDFCBANK','HEROMOTOCO','HINDALCO','HINDUNILVR','ICICIBANK','INDUSINDBK','INFY','IOC','ITC','JSWSTEEL','KOTAKBANK','LT','M&M','MARUTI','NESTLEIND','NTPC','ONGC','POWERGRID','RELIANCE','SHREECEM','SBIN','SUNPHARMA','TCS','TATAMOTORS','TATASTEEL','TECHM','TITAN','ULTRACEMCO','UPL','VEDL','WIPRO','ZEEL']

Step 4: Running Python code to extract data and fetch it into csv file

Once you execute the code, data fetching will start from the API and it will start writing in the CSV file. Once the data writing is complete you can use it for analytics and drawing insights. We will discuss that in the next article.
