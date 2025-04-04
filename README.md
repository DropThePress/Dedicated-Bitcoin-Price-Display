# Bitcoin Price Display Clock

Turn any old mobile phone into a dedicated Bitcoin price display! This single HTML file connects to multiple price APIs (with automatic failover between 10 sources) to show the current BTC price as large as possible on your screen.

![Screenshot](Screenshot 2025-04-04 084410.png)

## Features

- **Giant Price Display**: Shows the Bitcoin price as large as possible on your screen
- **Multiple APIs**: Connects to 10 different price sources
- **Automatic Failover**: If one API fails, it switches to the next automatically
- **Dynamic Update Frequency**: Uses the fastest API available (as quick as 1-second updates)
- **Auto-scaling**: Adapts to any screen size or orientation
- **Fullscreen Mode**: Tap anywhere to toggle fullscreen

## How to Use

1. Download the [BitcoinDisplayClock.html](BitcoinDisplayClock.html) file
2. Open it in any web browser on your phone
3. Tap the screen to go fullscreen
4. Keep your device plugged in for a permanent display
5. RECOMMENDED: use a very slow charger to extend the life of the device

## API Sources

The display uses these price sources (in order of priority):

1. Binance (1 second updates)
2. Coinbase (5 second updates)
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
