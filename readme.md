# n-gon
> Create regular polygons with `n` sides

![stop sign](stop.png "hmmm")

## install
```sh
npm install n-gon
```

## usage
```js
const gon = require('n-gon')

var polygon = gon(7)
  .map(point => ({
    x: canvas.width / 2 + point.x * size,
    y: canvas.height / 2 + point.y * size
  }))
```

## license
[MIT](https://opensource.org/licenses/MIT) © [Brandon Semilla](https://git.io/semibran)
