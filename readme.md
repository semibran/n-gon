# n-gon
> Create regular polygons with `n` sides

![stop sign](stop.png "hmmm")

## install
```sh
npm install n-gon
```

## usage
A "polygon" is just an array of `{ x, y }` points, which allows you to `map` it to a new size and position.
```js
const gon = require('n-gon')

var polygon = gon(7)
  .map(point => ({
    x: point.x * size + offset.x,
    y: point.y * size + offset.y
  }))
```

## license
[MIT](https://opensource.org/licenses/MIT) © [Brandon Semilla](https://git.io/semibran)
