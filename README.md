# CSS Diff

Get the diff between two css.

## Installation

```shell
$ npm install github:itccompliance/css-diff#v1.0.4
```

## Usage

```js
const cssDiff = require('@itccompliance/css-diff')

const cssA = `
body {
  background: white;
  color: red;
}
`

const cssB = `
body {
  background: white;
  color: blue;
}
`

const diff = cssDiff(cssA, cssB)
// body {
//   color: blue;
// }
```
