# Webpack

Для начала работы следует установить:

- Последнию версию [Node](https://nodejs.org/en/)
- Последнию версию [Yarn](https://yarnpkg.com/lang/en/)

Базовая настройка [Webpack 4](https://webpack.js.org/) для bundle .scss/.js с транспилляцией кода через [Babel](https://babeljs.io/). Для актуальности, вместо [Extract-text-webpack-plugin](https://github.com/webpack-contrib/extract-text-webpack-plugin) был использован модуль [Mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin), так же был добавлен [Autoprefixer](https://github.com/postcss/autoprefixer), [postcss-prefix-selector](https://github.com/radvalentin/postcss-prefix-selector),
 [HtmlWebpackPlugin](https://github.com/jantimon/html-webpack-plugin) и config [Stylelint](https://stylelint.io/) (использую [VScode-stylelint](https://github.com/shinnn/vscode-stylelint))

Команды запуска:

- Установка зависимостей

```sh
yarn
```

- Запуск режима разработки

```sh
yarn dev
```

- Билдинг

```sh
yarn build
```

- Production

```sh
yarn prod
```
- Watch
```sh
yarn watch
```
