# css-font-weight

Functional CSS for font-weight

## Filesize

| File | Size |
|------|------|
| `dist/font-weight.css` | 2097 bytes |
| `dist/font-weight.min.css` | 1365 bytes (286 Gzipped) |

## Install

```sh
npm install css-font-weight
```

## Usage

### Import

```css
@import "css-font-weight";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-font-weight/dist/font-weight.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-font-weight/dist/font-weight.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.fw-normal` | `font-weight: normal;` |
| `.b` | `font-weight: bold;` |
| `.fw-lighter` | `font-weight: lighter;` |
| `.fw-bolder` | `font-weight: bolder;` |
| `.fw1` | `font-weight: 100;` |
| `.fw2` | `font-weight: 200;` |
| `.fw3` | `font-weight: 300;` |
| `.fw4` | `font-weight: 400;` |
| `.fw5` | `font-weight: 500;` |
| `.fw6` | `font-weight: 600;` |
| `.fw7` | `font-weight: 700;` |
| `.fw8` | `font-weight: 800;` |
| `.fw9` | `font-weight: 900;` |
| `.fw-normal-s` | `font-weight: normal;` |
| `.b-s` | `font-weight: bold;` |
| `.fw-lighter-s` | `font-weight: lighter;` |
| `.fw-bolder-s` | `font-weight: bolder;` |
| `.fw1-s` | `font-weight: 100;` |
| `.fw2-s` | `font-weight: 200;` |
| `.fw3-s` | `font-weight: 300;` |
| `.fw4-s` | `font-weight: 400;` |
| `.fw5-s` | `font-weight: 500;` |
| `.fw6-s` | `font-weight: 600;` |
| `.fw7-s` | `font-weight: 700;` |
| `.fw8-s` | `font-weight: 800;` |
| `.fw9-s` | `font-weight: 900;` |
| `.fw-normal-m` | `font-weight: normal;` |
| `.b-m` | `font-weight: bold;` |
| `.fw-lighter-m` | `font-weight: lighter;` |
| `.fw-bolder-m` | `font-weight: bolder;` |
| `.fw1-m` | `font-weight: 100;` |
| `.fw2-m` | `font-weight: 200;` |
| `.fw3-m` | `font-weight: 300;` |
| `.fw4-m` | `font-weight: 400;` |
| `.fw5-m` | `font-weight: 500;` |
| `.fw6-m` | `font-weight: 600;` |
| `.fw7-m` | `font-weight: 700;` |
| `.fw8-m` | `font-weight: 800;` |
| `.fw9-m` | `font-weight: 900;` |
| `.fw-normal-l` | `font-weight: normal;` |
| `.b-l` | `font-weight: bold;` |
| `.fw-lighter-l` | `font-weight: lighter;` |
| `.fw-bolder-l` | `font-weight: bolder;` |
| `.fw1-l` | `font-weight: 100;` |
| `.fw2-l` | `font-weight: 200;` |
| `.fw3-l` | `font-weight: 300;` |
| `.fw4-l` | `font-weight: 400;` |
| `.fw5-l` | `font-weight: 500;` |
| `.fw6-l` | `font-weight: 600;` |
| `.fw7-l` | `font-weight: 700;` |
| `.fw8-l` | `font-weight: 800;` |
| `.fw9-l` | `font-weight: 900;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fw-normal-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/font-weight.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/font-weight.css` — formatted
- `dist/font-weight.min.css` — minified

## License

MIT
