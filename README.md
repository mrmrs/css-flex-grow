# css-flex-grow

Functional CSS for flex-grow

## Filesize

| File | Size |
|------|------|
| `dist/flex-grow.css` | 797 bytes |
| `dist/flex-grow.min.css` | 513 bytes (163 Gzipped) |

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
| `.fg-1` | `flex-grow: 1;` |
| `.fg-2` | `flex-grow: 2;` |
| `.fg-3` | `flex-grow: 3;` |
| `.fg-4` | `flex-grow: 4;` |
| `.fg-i` | `flex-grow: inherit;` |
| `.fg-1-s` | `flex-grow: 1;` |
| `.fg-2-s` | `flex-grow: 2;` |
| `.fg-3-s` | `flex-grow: 3;` |
| `.fg-4-s` | `flex-grow: 4;` |
| `.fg-i-s` | `flex-grow: inherit;` |
| `.fg-1-m` | `flex-grow: 1;` |
| `.fg-2-m` | `flex-grow: 2;` |
| `.fg-3-m` | `flex-grow: 3;` |
| `.fg-4-m` | `flex-grow: 4;` |
| `.fg-i-m` | `flex-grow: inherit;` |
| `.fg-1-l` | `flex-grow: 1;` |
| `.fg-2-l` | `flex-grow: 2;` |
| `.fg-3-l` | `flex-grow: 3;` |
| `.fg-4-l` | `flex-grow: 4;` |
| `.fg-i-l` | `flex-grow: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fg-1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-grow.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-grow.css` — formatted
- `dist/flex-grow.min.css` — minified

## License

MIT
