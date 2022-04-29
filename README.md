# Web Component Library Starter Kit

"Why create components for a specific framework when it can be written to be understood by all — including browsers?"

## 👋🏼 Introduction

Before you get started, it's is important to understand what a Web Component is. Think of it as a (custom) HTML element. That being said, this is an opinionated starter kit to help you expedite the development of your component library.

### 👩🏽‍💻 Dev Tools

- [Vite 2.9](https://vitejs.dev/) - "Next Generation Frontend Tooling"
- [Vue 3.2](https://vuejs.org/) - write Web Components the same way you would write SFCs
- [TypeScript 4.6](https://www.typescriptlang.org/)
- [Vitest](https://github.com/vitest-dev/vitest) - Unit testing powered by Vite
- [Cypress](https://cypress.io/) - E2E testing
- [UnoCSS](https://github.com/unocss/unocss) - create your own style guide with ease
- [Renovate](https://renovatebot.com/) - automatic PR dependency updates
- [GitHub Actions](https://github.com/features/actions) - automatically fixes code style issues, tags releases, and runs the test suite
- [VS Code Extensions](./.vscode/extensions.json)
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 `<script setup>` IDE support

### 🧩 Plugins

- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - components auto import
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Directly use Vue Composition API and others without importing
- [VueUse](https://github.com/vueuse/vueuse) - Collection of useful composition APIs

### 🥰 Coding Style

- Use Composition API with [`<script setup>` SFC syntax](https://github.com/vuejs/rfcs/pull/227)
  - [Reactivity Transform](https://vuejs.org/guide/extras/reactivity-transform.html) enabled
- [ESLint](https://eslint.org/) - statically analyzes your code to quickly find problems
- [Prettier](https://prettier.io/) - Opinionated code formatting, like Tailwind class name sorting

## 💡 Get Started

It's very easy to get started, especially if you have designed/developed Vue Single File Components before. Check out the index.html and how the `HelloWorld`-component is defined within this repo. Feel free to create any component.

```bash
npx degit openweblabs/web-components-library-starter my-wc-library
cd my-wc-library
pnpm i # if you don't have pnpm installed, run `npm install -g pnpm`

# starts the local server at http://localhost:3333/ & watches for changes
pnpm dev

# builds the library for production-ready use
pnpm build
```

Additionally, the `package.json` contains some useful snippets you likely want to be aware of.

## 🖥️ Browsers

This starter kit is built for the modern web and avoids bloated polyfills and outdated environments as much as possible. Currently, it supports all browsers that fully implement the [Custom Elements V1][caniuse-custom-el-v1].

- Edge 79+
- Firefox 63+
- Chrome 67+
- Safari 13.1+
- Opera 64+
- iOS Safari 13.7+
- Android Browser 81+
- Opera Mobile 59+
- Chrome for Android 88+

[caniuse-custom-el-v1]: https://caniuse.com/custom-elementsv1

## 🧪 Testing

```bash
yarn test
```

## 📈 Changelog

Please see our [releases](https://github.com/openweblabs/web-components-library-starter/releases) page for more information on what has changed recently.

## 💪🏼 Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## 🏝 Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[Discussions on GitHub](https://github.com/openweblabs/web-components-library-starter/discussions)

For casual chit-chat with others using this package:

[Join the Meema Discord Server](https://discord.meema.io)

## 📄 License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.

Made with ❤️ by Meema Labs. And many thanks to [antfu](https://github.com/antfu)!
