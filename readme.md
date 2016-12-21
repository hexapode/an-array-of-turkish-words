# an-array-of-turkish-words

An array of ~195,00 Turkish words derived from internet and sort by popularity. Works with node and browserify.

Inspired / Fork from https://github.com/zeke/an-array-of-english-words

## Programmatic Usage

To use the module in Javascript code, install it locally:

```sh
npm install an-array-of-turkish-words --save
```

Then:

```js
var words = require("an-array-of-turkish-words")
var funWords = words.filter(function(w) { return !!w.match(/^fun/i) })
console.log(funWords)
```

## Command Line Usage

There's a CLI that prints all words to STDOUT. Install it globally:

```sh
npm i -g an-array-of-turkish-words
kelime | grep peynir
```
