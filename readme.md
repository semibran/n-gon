# n-gon
> create regular polygons with `n` sides

![stop sign](stop.png "hmmm")

## usage
[![npm badge]][npm package]

A "polygon" is just an array of `[ x, y ]` points, which allows you to map it to a new size and position.
```js
const gon = require('n-gon')

let polygon = gon(7)
  .map(([ x, y ]) => [
    x * size + offset[0],
    y * size + offset[1]
  ])
```

[npm badge]:      https://nodei.co/npm/n-gon.png?mini
[npm package]:    https://www.npmjs.com/package/n-gon
