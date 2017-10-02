# eslint-config-requarks

An ESLint configuration (eslint-config-requarks), based on the StandardJS rules, but with a few modifications.

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about [Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the official ESLint website.

To use the JavaScript Standard Style shareable config, first run this:

```bash
npm install --save-dev eslint-config-requarks eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node
```

Then, add this to your `.eslintrc` file:

```json
{
  "extends": "requarks"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

## Rules

eslint-config-requarks is based on [StandardJS]((http://standardjs.com)) with the following changes:

- No space before function parenthese enforcement (`space-before-function-paren` removed)
- No enforcement of error variable handling in catch statements (`handle-callback-err` removed)
