# allthecars

A complete list of all cars and other vehicles in [Greenville](https://www.roblox.com/games/891852901/).

## Why?

The developers provide no official or complete list of cars, making it difficult to implement it programmatically. Example use cases include registration systems and generating statistics.

This works well with [allthestates](https://github.com/gvrealism/allthestates).

## Installation

```bash
npm install --save https://github.com/gvrealism/allthecars
```

This will allow you to import or/and require the package. If you're not using Node.js, you can fetch the list from the [file](https://raw.githubusercontent.com/gvrealism/allthecars/v2/index.js).

## Usage

```js
const cars = require('allthecars')
const exists = (name) => cars.includes(name) 
```

## License

[ISC](https://github.com/gvrealism/allthecars/tree/v2/LICENSE)
