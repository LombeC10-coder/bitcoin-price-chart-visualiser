# Bitcoin Price Chart Visualiser

A Python desktop application that fetches Bitcoin OHLC market data from the CoinGecko API and displays interactive Bitcoin price charts using Pandas, Pygame and mplfinance.

This project started as part of a group project with two other students. I later extended and refined my own version by improving the structure, chart display, caching, error handling and project documentation.

---

## Features

- Fetches Bitcoin OHLC market data from the CoinGecko API
- Displays candlestick charts for selected timeframes
- Supports multiple timeframes:
  - 1 Day
  - 1 Week
  - 1 Month
  - 1 Year
  - Max / All Time
- Uses Pandas to structure and process time-series market data
- Uses mplfinance and Matplotlib to generate financial charts
- Uses Pygame to create an interactive desktop interface
- Includes light mode and dark mode
- Shows a price tooltip based on mouse position
- Uses local caching to reduce repeated API calls
- Includes a refresh shortcut to reload the current data

---

## Technologies Used

- Python
- Pandas
- Requests
- mplfinance
- Matplotlib
- Pygame
- CoinGecko API

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/LombeC10-coder/bitcoin-price-chart-visualiser.git
cd bitcoin-price-chart-visualiser
