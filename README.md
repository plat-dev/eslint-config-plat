<div align="center">
  <h1>eslint-config-plat</h1>
</div>

<p align="center">
  ESLint <a href="http://eslint.org/docs/developer-guide/shareable-configs.html">shareable config</a> for the Plat JavaScript style guide
</p>

<div align="center">
  <a href="https://circleci.com/gh/plat-dev/eslint-config-plat">
    <img alt="CircleCI" src="https://circleci.com/gh/plat-dev/eslint-config-plat.svg?style=shield" />
  </a>
  <a href="https://badge.fury.io/js/eslint-config-plat">
    <img alt="npm version" src="https://badge.fury.io/js/eslint-config-plat.svg" />
  </a>
  <a href="https://www.npmjs.com/package/eslint-config-plat">
    <img alt="npm" src="https://img.shields.io/npm/dt/eslint-config-plat.svg" />
  </a>
  <a href="https://david-dm.org/plat-dev/eslint-config-plat">
    <img alt="npm" src="https://img.shields.io/david/plat-dev/eslint-config-plat.svg?style=flat-square" />
  </a>
  <a href="https://opensource.org/licenses/mit-license.php">
    <img alt="MIT Licence" src="https://badges.frapsoft.com/os/mit/mit.svg?v=103" />
  </a>
  <a href="https://github.com/ellerbrock/open-source-badge/">
    <img alt="Open Source Love" src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" />
  </a>
</div>

<br />


## Installation

```
# NPM
$ npm install --save-dev eslint eslint-config-plat
# Yarn
$ yarn add -D eslint eslint-config-plat
```


## Usage

Once the `eslint-config-plat` package is installed, you can use it by specifying `plat` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "plat",
  "rules": {
    // Additional, per-project rules...
  }
}
```

### Using the `plat` config with `eslint:recommended`

There are several rules in the [`eslint:recommended` ruleset](http://eslint.org/docs/rules/) that plat style is not opinionated about that you might want to enforce in your project.

To use plat style in conjunction with ESLint's recommended rule set, extend them both, making sure to list `plat` last:

```js
{
  "extends": ["eslint:recommended", "plat"],
  "rules": {
    // Additional, per-project rules...
  }
}
```


## License

Provided under the terms of the [MIT License](https://github.com/plat-dev/eslint-config-plat/blob/master/LICENSE).

Copyright © 2017, [PLAT](http://www.plat.com).
