
# `@gec.js/react-prettier-config`

A configuration for prettier, to create consistancy across multiple projects.

Based on LBHackney-IT work, @hackney/prettier-config:1.0.1

## Usage

Install package as a dev dependency:

```
npm install @gec.js/react-prettier-config -D
// or
yarn add @gec.js/react-prettier-config -D
```

Create a `.prettierrc.js` file in the root of your project.

```js
const prettierConfig = require("@gec.js/react-prettier-config");

module.exports = prettierConfig;
```

To apply overrides of any of the options:

```js
const prettierConfig = require("@gec.js/react-prettier-config");

module.exports = {
  ...prettierConfig,
  semi: false,
};
```
