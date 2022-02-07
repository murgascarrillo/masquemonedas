# Más que monedas

Este repo contiene 1 base de código que usa el [API de Coingecko](https://www.coingecko.com/en/api) para recuperar el valor actual de tus monedas. Está destinado a propósitos educativos solamente - **esto no es bajo ninguna circunstancia un producto completo/testeado**. 

This repo contains 1 code base that use the [CoinGecko API](https://www.coingecko.com/en/api) to retrieve the current values of your coins. It's meant for education purposes only - **these are by no means a complete/tested product**.

## Uso / Usage

Necesitarás actualizar un arreglo JSON con los símbolos de las monedas requeridas y las unidades que tengas. Luego que la APP arranca, el valor actual en dólares y el total será mostrado.

You'll need to update a JSON array with the coin symbols you want and the units you have. After the apps run, the current dollar value and the total will be displayed.

### Consiguiendo los símbolos / Getting the symbols

Para conseguir todas los símbolos de las monedas para tu portafolio, ve a [esta respuesta de API](https://api.coingecko.com/api/v3/coins/list) y busca tus monedas.

To get all available coin symbols for your portfolio, go to [this API response](https://api.coingecko.com/api/v3/coins/list) and search for your coins.

### Estructura del Portafolio / Portfolio structure

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

## Aplicación disponible / Available application

### 1. HTML app

#### Requerimientos / Requirements

1. Un navegador moderno
1. Un editor de texto
--
1. A modern browser
1. A text editor

#### Uso / Usage

1. Edita el archivo 'portfolio.js' con las monedas que tengas, y el número de unidades.
1. Abre 'portfolio.html' en el navegador.
--
1. Edit the file "portfolio.js" with the coins you have, and the number of units.
1. Open "portfolio.html in the browser.

## Licencia / License

La fuente tiene licencia MIT. Eres libre de usarlo, cambiarlo, y hacerlo que quieras con esto 😀.

The source is licensed under MIT license. You are free to use it, change it, and do whatever you want with it 😀.

## Birra / Beer! 🍻

Si sientes que este código es educativo, entretenido, o útil para ti en cualquier forma, dejame algo de dinero para 🍺 en la forma de XNO/VITE/ETH/BAT/DAI/loquesea at **[carlosmurgas.crypto](https://etherscan.io/address/0x94c732aae0b82cb594b9c4f61e7a8779003b8773)**.
Si no tienes claro si la moneda que quieres darme puede pasar a través de esa dirección corta, escríbeme en Twitter o reddit: elperfilbajo

También, si quieres dejar algo de eso también en los bolsillos del creador del código original, envíaselo a **[guy.wantsome.eth](https://etherscan.io/address/guy.wantsome.eth)**.

If you feel like this code is educational, entertaining, or useful to you in any way, drop me some 🍺 money in the shape of XNO/VITE/ETH/BAT/DAI/whatever at **[carlosmurgas.crypto](https://etherscan.io/address/0x94c732aae0b82cb594b9c4f61e7a8779003b8773)**.
If you are not sure if the currency you may be wanting to tip me can go thru that short address, reach out to me on Twitter or reddit: elperfilbajo

Plus, if you want to drop some of that into the original code maker's pocket, send it at **[guy.wantsome.eth](https://etherscan.io/address/guy.wantsome.eth)**.
