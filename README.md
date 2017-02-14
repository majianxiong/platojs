# PLATOJS

> Libraries for PLATO

## Install

```bash
$ npm install platojs -S
```

## Usage

Components

```js
import xxx from 'platojs/components/xxx'
```

Directives

```js
import xxx from 'platojs/directives/xxx'
```

Plugins

```js
import xxx from 'platojs/plugins/xxx'
```

Util

```js
import xxx from 'platojs/util/xxx'
```

System

```js
import xxx from 'platojs/system/xxx'
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
