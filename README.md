# dre1080 Prettier Config

[![npm (scoped)](https://img.shields.io/npm/v/@dre1080/prettier-config)](https://www.npmjs.org/package/@dre1080/prettier-config)

> A sharable prettier config object.

## Install

Install [prettier](https://prettier.io/) and `@dre1080/prettier-config`:

**With Yarn**

```sh
$ yarn add --dev prettier @dre1080/prettier-config
```

**With npm**

```sh
$ npm install prettier @dre1080/prettier-config --save-dev
```

## Usage

Add the `prettier` key to your `package.json`:

```json
"prettier": "@dre1080/prettier-config"
```

or create a `.prettierrc.js` with the following contents:

```js
module.exports = {
  ...require("@dre1080/prettier-config"),
};
```

[Check out the `prettier` documentation for more info on sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations).
