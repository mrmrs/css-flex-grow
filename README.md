# css-flex-grow 0.0.7

Css module of single purpose classes for flex grow

#### Stats

206 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-grow
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-grow
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-grow";
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
<link rel="stylesheet" href="path/to/module/css/css-flex-grow">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX GROW
*/
.fg-1 { flex-grow: 1; }
.fg-2 { flex-grow: 2; }
.fg-3 { flex-grow: 3; }
.fg-4 { flex-grow: 4; }
.fg-i { flex-grow: inherit; }
@media screen and (min-width: 48em) {
 .fg-1-ns { flex-grow: 1; }
 .fg-2-ns { flex-grow: 2; }
 .fg-3-ns { flex-grow: 3; }
 .fg-4-ns { flex-grow: 4; }
 .fg-i-ns { flex-grow: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fg-1-m { flex-grow: 1; }
 .fg-2-m { flex-grow: 2; }
 .fg-3-m { flex-grow: 3; }
 .fg-4-m { flex-grow: 4; }
 .fg-i-m { flex-grow: inherit; }
}
@media screen and (min-width: 64em) {
 .fg-1-l { flex-grow: 1; }
 .fg-2-l { flex-grow: 2; }
 .fg-3-l { flex-grow: 3; }
 .fg-4-l { flex-grow: 4; }
 .fg-i-l { flex-grow: inherit; }
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
