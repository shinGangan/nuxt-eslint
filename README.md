# Nuxt ESLint Config

[ESlint](https://eslint.org/) config used for Nuxt.js

## Usage

Do you want to add the config to your own projects? There you go:

1. Add this package to your devDependencies (`npm i -D @nuxtjs/eslint-config` or `yarn add -D @nuxtjs/eslint-config`)
2. Add the [`peerDependencies`](./package.json) to your project

`npm i -D eslint eslint-config-standard eslint-plugin-import eslint-plugin-jest eslint-plugin-node eslint-plugin-promise eslint-plugin-standard eslint-plugin-vue`

3. Create a `.eslintrc.js` file

4. Extend our config (you can use just the scope name as ESLint will assume the `eslint-config` prefix):

```json
{
  "extends": [
    "@nuxtjs"
  ]
}
```


## License

Setup inspired by [eslint-config-standard](https://github.com/standard/eslint-config-standard)

MIT - Nuxt.js team
