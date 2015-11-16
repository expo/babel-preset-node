# babel-preset-node

Babel presets for modern Node.js.

## Why?

Node.js includes recent releases of V8, which implements some—but not all—of the features of modern JavaScript. Using Babel, we can use most of the latest features of JavaScript by transforming the source code into the subset of JavaScript that V8 supports.

`babel-preset-node` brings in the features of modern JavaScript while using V8's native implementations where possible.

## Installation and Usage

```sh
npm install @exponent/babel-preset-node --save-dev
```

Specify the preset in your Babel configuration. For example, you may create a file called `.babelrc` in your project's root directory that contains:

```json
{
  "presets": ["@exponent/babel-preset-node"]
}
```
