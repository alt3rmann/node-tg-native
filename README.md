# node-tg-native

[![NPM version](https://badge.fury.io/js/node-tg-native.svg)](https://npmjs.org/package/node-tg-native)

> Module to call native TDLib functions


## FFI

"ffi" module changed to "ffi-napi" for compatibility with node.js >= 9.0.0

## Installation

```sh
$ npm install --save node-tg-native
```

## Usage

```js
const nodeTgNative = require("node-tg-native");
const td = new nodeTgNative();

td.create();

td.subscribe(response => {
  console.log(response);
});
```

## License

MIT © [k-egor-smirnov]()
