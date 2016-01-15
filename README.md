# css-font-weight 0.0.7

Css module of single purpose classes for font weight

#### Stats

340 | 52 | 52
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-font-weight
```

#### With Git

```
git clone https://github.com/tachyons-css/css-font-weight
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-font-weight";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-font-weight">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FONT WEIGHT
*/
.fwn { font-weight: normal; }
.b { font-weight: bold; }
.fw-light { font-weight: lighter; }
.fw-bolder { font-weight: bolder; }
.fw1 { font-weight: 100; }
.fw2 { font-weight: 200; }
.fw3 { font-weight: 300; }
.fw4 { font-weight: 400; }
.fw5 { font-weight: 500; }
.fw6 { font-weight: 600; }
.fw7 { font-weight: 700; }
.fw8 { font-weight: 800; }
.fw9 { font-weight: 900; }
@media screen and (min-width: 48em) {
 .fwn-ns { font-weight: normal; }
 .b-ns { font-weight: bold; }
 .fw-light-ns { font-weight: lighter; }
 .fw-bolder-ns { font-weight: bolder; }
 .fw1-ns { font-weight: 100; }
 .fw2-ns { font-weight: 200; }
 .fw3-ns { font-weight: 300; }
 .fw4-ns { font-weight: 400; }
 .fw5-ns { font-weight: 500; }
 .fw6-ns { font-weight: 600; }
 .fw7-ns { font-weight: 700; }
 .fw8-ns { font-weight: 800; }
 .fw9-ns { font-weight: 900; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fwn-m { font-weight: normal; }
 .b-m { font-weight: bold; }
 .fw-light-m { font-weight: lighter; }
 .fw-bolder-m { font-weight: bolder; }
 .fw1-m { font-weight: 100; }
 .fw2-m { font-weight: 200; }
 .fw3-m { font-weight: 300; }
 .fw4-m { font-weight: 400; }
 .fw5-m { font-weight: 500; }
 .fw6-m { font-weight: 600; }
 .fw7-m { font-weight: 700; }
 .fw8-m { font-weight: 800; }
 .fw9-m { font-weight: 900; }
}
@media screen and (min-width: 64em) {
 .fwn-l { font-weight: normal; }
 .b-l { font-weight: bold; }
 .fw-light-l { font-weight: lighter; }
 .fw-bolder-l { font-weight: bolder; }
 .fw1-l { font-weight: 100; }
 .fw2-l { font-weight: 200; }
 .fw3-l { font-weight: 300; }
 .fw4-l { font-weight: 400; }
 .fw5-l { font-weight: 500; }
 .fw6-l { font-weight: 600; }
 .fw7-l { font-weight: 700; }
 .fw8-l { font-weight: 800; }
 .fw9-l { font-weight: 900; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

