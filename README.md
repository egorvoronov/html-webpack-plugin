HTML Webpack Plugin With Template Variables
The same as html-webpack-plugin but enables to pass template variables as root variables instead of getting vars from htmlWebpackPlugin.options

Installation
------------
Install the plugin with npm:
```shell
$ npm install html-webpack-plugin-template-vars --save-dev
```

```js
const webpackPlugins = [
  new HtmlWebpackPlugin({
    template: 'index.ejs',
    templateVariables: {
        hello: 'world',
        foo: 'baz',
    }
  }),
];
```

# License

This project is licensed under [MIT](https://github.com/jantimon/html-webpack-plugin/blob/master/LICENSE).
