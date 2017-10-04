# DevExtreme with Webpack and Knockout

This starter project has been created by [generator-devextreme](https://github.com/oliversturm/generator-devextreme) version 1.0.6 and includes [Knockout](http://knockoutjs.com/) and [DevExtreme](https://js.devexpress.com/) widgets. 

These options were used to generate the project:

```
{
  "appname": "demo-generator-devextreme-knockout-intl-webpack",
  "apptype": "knockout",
  "localization": "intl",
  "locales": [
    "de",
    "ja",
    "en-GB"
  ],
  "bundling": "webpack",
  "language": "js"
}
```

Based on the options, localization support has been included on the basis of [Intl](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Intl) and the [DevExtreme-Intl](https://github.com/DevExpress/DevExtreme-Intl) library. In addition to the language files for the 'en' locale, which are included by default, the following locales have also been added: de, ja, en-GB.

## Running the project

Install dependencies:

```shell
npm install
```

Run the development web server:

```shell
npm start
```

## Building for production

A build script is provided to build with the production configuration in `webpack.prod.js`:

```shell
npm run build
```

