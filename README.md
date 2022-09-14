# @jevon617/eslint-config

ESLint config for JavaScript, TypeScript, Vue 2, Vue 3.

Forked from [sxzz/eslint-config](https://github.com/antfu/eslint-config)

- Single quotes, no semi
- Auto fix for formatting (aimed to be used standalone without Prettier)
- TypeScript, Vue, JavaScript out-of-box
- Lint also for json, yaml, markdown
- Sorted imports, dangling commas for cleaner commit diff
- Reasonable defaults, best practices, only one-line of config

## Usage

```bash
pnpm i -D @jevon617/eslint-config-basic # JavaScript only
pnpm i -D @jevon617/eslint-config-ts # JavaScript and TypeScript
pnpm i -D @jevon617/eslint-config-vue # TypeScript and Vue3
```

## Quick start

### Vue 3

```bash
pnpm i -D @jevon617/eslint-config-vue
```

```javascript
// .eslintrc.js
module.exports = {
  root: true,
  extends: ['@jevon617/eslint-config-vue'],
  rules: {
    // Your custom rules
  },
}
```

### VSCode

```jsonc
// settings.json
{
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ],
  "eslint.probe": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ]
}
```

## License

MIT License © 2021-PRESENT [jevon617](https://github.com/jevon617)
