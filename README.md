# COINbet
https://coinbet.netlify.app/
<div align='center'><img style="width:16%" src='https://user-images.githubusercontent.com/105128267/220607693-29987a1c-8f0d-4835-9bfe-3b5c9f326b17.png'/></div>
COINbet is a website that allows users to search for information about various cryptocurrencies in real-time. The website is designed to provide users with accurate and up-to-date information about the price, market cap, trading volume, and other key metrics of cryptocurrencies. The information is obtained using the _CoinGecko API_, which provides up-to-date market data for various cryptocurrencies.

## Features

- Displays the current market price, 24-hour price change, market capitalization, and trading volume for the top 4 cryptocurrencies (Bitcoin, Ethereum, Binance Coin, and Cardano) in USD.
- Allows users to clickon a cryptocurrency to view more detailed information, including a description, website link, and social media links for the cryptocurrency.

## Demo
 ![screenshot (12)](https://github.com/abhishek-06-singh/CoinBet/assets/115978151/093c4d50-c7b8-4716-aa83-b9381b8dea80)
 
## Technologies Used

```H
- React.js for building the front-end user interface
HTTP requests to the CoinGecko API
Font Awesome for displaying icons
React Router for navigation
```

## Installation and Usage

- Clone the repository: git clone https://github.com/your-username/COINbet.git
- Install dependencies: npm install
- Start the development server: npm start
- Open a web browser and navigate to http://localhost:3000/

## API Rate Limit

The CoinGecko API has a rate limit of 50 requests per minute. If you exceed this limit, you will receive a 429 Too Many Requests error. To avoid this, the website caches the cryptocurrency data for 1 minute before making a new request to the API.
