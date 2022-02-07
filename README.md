# Crypto Portfolio

This repo contains 1 code base that use the [CoinGecko API](https://www.coingecko.com/en/api) to retrieve the current values of your coins. It's meant for education purposes only - **these are by no means a complete/tested product**.

## Usage

You'll need to update a JSON array with the coin symbols you want and the units you have. After the apps run, the current dollar value and the total will be displayed.

### Getting the symbols

To get all available coin symbols for your portfolio, go to [this API response](https://api.coingecko.com/api/v3/coins/list) and search for your coins.

### Portfolio structure

```json
[
  {
    "coin": "bitcoin",
    "units": 0.0000000001
  },
  {
    "coin": "ethereum",
    "units": 0.000001
  },
  {
    "coin": "cardano",
    "units": 1
  }
]
```

## Available application

### 1. HTML app

#### Requirements

1. A modern browser
1. A text editor

#### Usage

1. Edit the file "portfolio.js" with the coins you have, and the number of units.
1. Open "portfolio.html in the browser.

## License

The source is licensed under MIT license. Feel free to use it, change it, and do whatever you want with it 😀.

## Beer! 🍻

If you feel like this code is educational, entertaining, or useful to you in any way, drop me some 🍺 money in the shape of XNO/VITE/ETH/BAT/DAI/whatever at **[carlosmurgas.crypto](https://etherscan.io/address/0x94c732aae0b82cb594b9c4f61e7a8779003b8773)**.
If you are not sure if the currency you may be wanting to tip me can go thru that short address reach out to me on Twitter or reddit: elperfilbajo

Plus, if you want to drop some of that into the original code maker's pocket, send it at **[guy.wantsome.eth](https://etherscan.io/address/guy.wantsome.eth)**.
