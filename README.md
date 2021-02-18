# @eoet/eslint-config

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html)

## Installation

### yarn

```
yarn add --dev @eoet/eslint-config
```

### npm

```
npm install --save-dev @eoet/eslint-config
```

## Usage

Once the `@eoet/eslint-config` package is installed, you can use it by specifying `@eoet` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "@eoet",
  "rules": {
    // Additional, per-project rules...
  }
}
```

### Using the `eoet` config with `eslint:recommended`

There are several rules in the [`eslint:recommended` ruleset](http://eslint.org/docs/rules/)

To use the Eoet style in conjunction with ESLint's recommended rule set, extend them both, making sure to list `@eoet` last:

```js
{
  "extends": ["eslint:recommended", "@eoet"],
  "rules": {
    // Additional, per-project rules...
  }
}
```

## License

MIT © Hiep Nguyen
