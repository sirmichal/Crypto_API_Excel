# Excel based Crypto dashboard
## Description

🪙 It is a fun and useful project that I created. This Excel-based tool can make cryptocurrency portfolio tracking easy and interactive. It's like a financial playground for crypto enthusiasts and data lovers. It's powered by real-time data from the CoinMarketCap API. It shows only a fraction of the possibilies which can be achieved, like analysis of past prices or gathering information about crypto trends. 

## Let's Take a Journey

### Step 1 - Data Source Selection: CoinMarketCap API Integration

🗺️ To kick things off, I needed a reliable source of crypto data, and that's where CoinMarketCap's API comes into play. There is a basic free plan which has enabled me to access the API which later will provide me necessary data. TO get the access I had to register to the developer portal.


<img width="800" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_1.png?raw=true">

### Step 2 - API Integration and Data Processing

🔗 I began by selecting the appropriate API endpoint based on CoinMarketCap's documentation. This crucial step ensures that the dashboard fetches the exact data I need. 


<img width="600" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_2.png">

🌐 I then opened the "Data From Web" option in Excel, filling in the necessary information to connect to the CoinMarketCap API accordingly to the guideline in the documentation. This integration seamlessly facilitates the continuous flow of data between the API and the future dashboard.

<img width="600" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_3.png">

### Step 3 - Data Processing with Power Query

📊 In this step, I utilized Power Query within Excel to prepare the data for analysis. Here's how I went about it:

1. **Convert Inputs to Table:** I initiated the process by converting the raw inputs into a structured table format.
<img width="650" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_4.png">

3. **Choose Necessary Columns:** Next, I selected the required columns from the available dataset. By doing so, I focused the analysis on the specific information I needed, simplifying the subsequent steps. For the purpose of this excercise I have choosen 4 Cryptocurrencies to use later. Bitcoin, Ethereum, Cardano and XRP.
<img width="650" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_5.png">

5. **Set the Format of the Columns:** To ensure the data is correctly interpreted, I applied appropriate formatting to the selected columns.
<img width="650" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_6.png">

7. **Create a Table in Excel:** After shaping the data in Power Query, I brought it into Excel as a structured table. This final table is the foundation for the subsequent analysis and visualization.
<img width="750" alt="image" src="https://github.com/sirmichal/Crypto_API_Excel/blob/main/Crypto_API_Excel_7.png">
