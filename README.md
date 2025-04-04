# Bitcoin Price Display Clock

Turn any old mobile phone into a dedicated Bitcoin price display! This single HTML file connects to multiple price APIs (with automatic failover between various sources) to show the current BTC price as large as possible on your screen.
     
## Features

- **Giant Price Display**: Shows the Bitcoin price as large as possible on your screen
- **Multiple APIs**: Sources are listed below in "API Sources"
- **Automatic Failover**: If one API fails, it switches to the next automatically
- **Dynamic Update Frequency**: Uses the fastest API available
- **Auto-scaling**: Adapts to any screen size or orientation
- **Fullscreen Mode**: Click anywhere to toggle fullscreen

## How to Use

Run in browser:  
- <a href="https://dropthepress.github.io/Bitcoin-Display-Clock/" target="_blank">Click here</a>
  
Download to run locally:  
- <a href="BitcoinDisplayClock.html" download>BitcoinDisplayClock.html</a>

## API Sources

The display auto connects to the fastest API source available:

1. Coinbase (5 second updates)
3. Bitstamp (5 second updates)
4. Gemini (7 second updates)
5. Bittrex (12 second updates)
6. Bitfinex (12 second updates)
7. Kraken (15 second updates)
8. Blockchain.info (15 second updates)
9. CoinGecko (45 second updates)
10. Coindesk (60 second updates)

## License

This project is free to use and modify.

## Screenshot

![Screenshot](Screenshot2025-04-04.png)
