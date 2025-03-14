# vueAgileFront

This template should help get you started developing with Vue 3 in Vite.

## important notice

这个是专门用来调试开发的库，正常用`yarn install` 获取依赖，然后用`yarn run dev`在浏览器打开终端中的链接即可

需要在vscode中查看时，用 `yarn run build` 打包

打包后生成的dist文件夹，将其复制替换到 `[vsagilenew](https://github.com/zyg0121/vsagilenew)`的 `media`中的同名文件夹中

然后在 `vsagilenew`项目中用 `F5`运行即可

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
