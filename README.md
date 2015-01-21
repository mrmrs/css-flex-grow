# CSS FLEX GROW

  Mobile-first classes for css-flex-grow.
  Set the desired css-flex-grow on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-flex-grow
```
View on [npm](https://www.npmjs.org/package/css-flex-grow)


## File Size

734B flex-grow.css
553B flex-grow.min.css
179B minified and gzipped

## The Code
```
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

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fg-1-m { flex-grow: 1; }
  .fg-2-m { flex-grow: 2; }
  .fg-3-m { flex-grow: 3; }
  .fg-4-m { flex-grow: 4; }
  .fg-i-m { flex-grow: inherit; }
}

@media screen and (min-width: 64em)  {
  .fg-1-l { flex-grow: 1; }
  .fg-2-l { flex-grow: 2; }
  .fg-3-l { flex-grow: 3; }
  .fg-4-l { flex-grow: 4; }
  .fg-i-l { flex-grow: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

