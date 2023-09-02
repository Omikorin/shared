# @omikorin/prettier-config

A curated `.prettierrc` with explicit config for every option.

## Installation

To install `@omikorin/prettier-config`, use your favourite package manager:

```bash
pnpm install -D @omikorin/prettier-config
```

## Usage

Create a file named `.prettierrc.js` in the project's root directory with the following code.

```js
const config = require('@omikorin/prettier-config');

module.exports = config;
```

or edit `package.json`:

```jsonc
{
  // ...
  "prettier": "@omikorin/prettier-config"
}
```

Alternatively, you can overwrite chosen options like this.

```js
const config = require('@omikorin/prettier-config');

module.exports = {
  ...config,
  useTabs: true,
};
```

We all know tabs are worse than spaces and should be avoided.

# License

This project is licensed under the terms of the [ISC license](https://github.com/Omikorin/shared/blob/main/LICENSE).
