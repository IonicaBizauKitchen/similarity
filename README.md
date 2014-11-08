# similarity 

How similar are these two strings?

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install similarity --save
```

## Usage

```js
var similarity = require("similarity")

similarity("food", "food") // 1
similarity("food", "fool") // 0.75
similarity("ding", "plow") // 0
similarity("chicken", "chick") // 0.714285714
similarity("es6-shim", "es6 shim") // 0.875

```

## Tests

```sh
npm install
npm test
```


## Dependencies

- [leven](https://github.com/sindresorhus/leven): Measure the difference between two strings using the fastest JS implementation of the Levenshtein distance algorithm


## Dev Dependencies

- [tap](https://github.com/isaacs/node-tap): A Test-Anything-Protocol library


## License

ISC

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_