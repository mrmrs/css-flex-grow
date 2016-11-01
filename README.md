# css-flex-grow 1.0.6

Css module of single purpose classes for flex grow

#### Stats

269 | 20 | 60
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-grow
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-flex-grow
```

ssh:
```
git clone git@github.com:tachyons-css/css-flex-grow.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-grow";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-flex-grow@1.0.6/css/css-flex-grow.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-flex-grow">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FLEX GROW
*/
.fg-1 { -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; }
.fg-2 { -webkit-box-flex: 2; -ms-flex-positive: 2; flex-grow: 2; }
.fg-3 { -webkit-box-flex: 3; -ms-flex-positive: 3; flex-grow: 3; }
.fg-4 { -webkit-box-flex: 4; -ms-flex-positive: 4; flex-grow: 4; }
.fg-i { -webkit-box-flex: inherit; -ms-flex-positive: inherit; flex-grow: inherit; }
@media screen and (min-width: 48em) {
 .fg-1-ns { -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; }
 .fg-2-ns { -webkit-box-flex: 2; -ms-flex-positive: 2; flex-grow: 2; }
 .fg-3-ns { -webkit-box-flex: 3; -ms-flex-positive: 3; flex-grow: 3; }
 .fg-4-ns { -webkit-box-flex: 4; -ms-flex-positive: 4; flex-grow: 4; }
 .fg-i-ns { -webkit-box-flex: inherit; -ms-flex-positive: inherit; flex-grow: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fg-1-m { -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; }
 .fg-2-m { -webkit-box-flex: 2; -ms-flex-positive: 2; flex-grow: 2; }
 .fg-3-m { -webkit-box-flex: 3; -ms-flex-positive: 3; flex-grow: 3; }
 .fg-4-m { -webkit-box-flex: 4; -ms-flex-positive: 4; flex-grow: 4; }
 .fg-i-m { -webkit-box-flex: inherit; -ms-flex-positive: inherit; flex-grow: inherit; }
}
@media screen and (min-width: 64em) {
 .fg-1-l { -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; }
 .fg-2-l { -webkit-box-flex: 2; -ms-flex-positive: 2; flex-grow: 2; }
 .fg-3-l { -webkit-box-flex: 3; -ms-flex-positive: 3; flex-grow: 3; }
 .fg-4-l { -webkit-box-flex: 4; -ms-flex-positive: 4; flex-grow: 4; }
 .fg-i-l { -webkit-box-flex: inherit; -ms-flex-positive: inherit; flex-grow: inherit; }
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

ISC

