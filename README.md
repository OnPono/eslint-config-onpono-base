# eslint-config-onpono-base

Base ESLint rules for OnPono codebases by extending Airbnb's extensible shared config.

## Usage

Our default export extends [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) ESLint rules, including ECMAScript 6+. It requires `eslint` and `eslint-plugin-import`.

1. `npm install --save-dev eslint-config-onpono-base eslint-plugin-import eslint`
2. add `"extends": "onpono-base"` to your .eslintrc
