# eslint-config-pretty-standard

A shareable eslint+prettier config based on standard.

This eslint config contains all
the [standard](https://github.com/feross/eslint-config-standard) rules that is
not about code style. The idea is that you use this config together
with [prettier](https://github.com/prettier/prettier).

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

Here's how to install everything you need:

```bash
npm install --save-dev eslint-config-pretty-standard eslint prettier
```

Then, add this to your .eslintrc file:

```
{
  "extends": ["pretty-standard"]
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.
