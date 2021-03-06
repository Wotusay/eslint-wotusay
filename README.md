<div align="center">
<h1>eslint-wotusay</h1>
</div>

<!-- prettier-ignore-start -->
[![version][version-badge]][package]
[![MIT License][license-badge]][license]
<!-- prettier-ignore-end -->

## Table of Contents

-   [Table of Contents](#table-of-contents)
-   [Installation](#installation)
-   [Usage](#usage)
-   [VS Code](#vs-code)

## Installation

This module should be installed as one of your project's `devDependencies`:

```
yarn add eslint-wotusay -D
```

## Usage

Then add the extends to your .eslintrc.js:

```js
module.exports = {
    extends: 'wotusay,
    rules: {
        // your overrides
    },
};
```

## VS Code

Using the eslint-plugin you can use these settings for autoformatting:

```js
"editor.formatOnSave": true,
"eslint.format.enable": true,
  "[javascript]": {
"editor.formatOnSave": false,
  "editor.defaultFormatter": "dbaeumer.vscode-eslint"
},
"[javascriptreact]": {
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "dbaeumer.vscode-eslint"
},
"[typescript]": {
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "dbaeumer.vscode-eslint"
},
"[typescriptreact]": {
  "editor.formatOnSave": false,
  "editor.defaultFormatter": "dbaeumer.vscode-eslint"
},
"editor.codeActionsOnSave": {
  "source.fixAll": true,
}
```

<!-- prettier-ignore-start -->
[npm]: https://www.npmjs.com
[node]: https://nodejs.org
[version-badge]:https://img.shields.io/npm/v/eslint-config-wotusay
[package]: https://www.npmjs.com/package/eslint-config-wotusay
[license-badge]: https://img.shields.io/npm/l/eslint-config-wotusay
[license]: https://github.com/Wotusay/eslint-wotusay/blob/main/LICENSE
<!-- prettier-ignore-end -->
# Story-map
