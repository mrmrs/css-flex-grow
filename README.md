# css-flex-grow

Functional CSS for flex-grow

## Filesize

| File | Size |
|------|------|
| `dist/flex-grow.css` | 1269 bytes |
| `dist/flex-grow.min.css` | 877 bytes (192 Gzipped) |

## Install

```sh
npm install css-flex-grow
```

## Usage

### Import

```css
@import "css-flex-grow";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-grow/dist/flex-grow.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-grow/dist/flex-grow.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.flex-grow1` | `flex-grow: .25;` |
| `.flex-grow2` | `flex-grow: .5;` |
| `.flex-grow3` | `flex-grow: 1;` |
| `.flex-grow4` | `flex-grow: 2;` |
| `.flex-grow5` | `flex-grow: 3;` |
| `.flex-grow6` | `flex-grow: 4;` |
| `.flex-grow-inherit` | `flex-grow: inherit;` |
| `.flex-grow1-s` | `flex-grow: .25;` |
| `.flex-grow2-s` | `flex-grow: .5;` |
| `.flex-grow3-s` | `flex-grow: 1;` |
| `.flex-grow4-s` | `flex-grow: 2;` |
| `.flex-grow5-s` | `flex-grow: 3;` |
| `.flex-grow6-s` | `flex-grow: 4;` |
| `.flex-grow-inherit-s` | `flex-grow: inherit;` |
| `.flex-grow1-m` | `flex-grow: .25;` |
| `.flex-grow2-m` | `flex-grow: .5;` |
| `.flex-grow3-m` | `flex-grow: 1;` |
| `.flex-grow4-m` | `flex-grow: 2;` |
| `.flex-grow5-m` | `flex-grow: 3;` |
| `.flex-grow6-m` | `flex-grow: 4;` |
| `.flex-grow-inherit-m` | `flex-grow: inherit;` |
| `.flex-grow1-l` | `flex-grow: .25;` |
| `.flex-grow2-l` | `flex-grow: .5;` |
| `.flex-grow3-l` | `flex-grow: 1;` |
| `.flex-grow4-l` | `flex-grow: 2;` |
| `.flex-grow5-l` | `flex-grow: 3;` |
| `.flex-grow6-l` | `flex-grow: 4;` |
| `.flex-grow-inherit-l` | `flex-grow: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.flex-grow1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-grow.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-grow.css` — formatted
- `dist/flex-grow.min.css` — minified

## License

MIT
