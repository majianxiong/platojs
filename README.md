# PLATOJS

> Libraries of PLATO

## Install

```bash
$ npm install platojs -S
```

## Usage

```js
import xxx from 'platojs/.../...'
```

## Webpack

```js
...
module: {
  rules: [
    ...
    {
      test: /\.js$/,
      // platojs needs babel
      exclude: /node_modules[/\\](?!platojs)/,
      loader: 'babel-loader'
    },
    ...
  ]
}
...
```

## Example

[https://github.com/platojs/plato](https://github.com/platojs/plato)
