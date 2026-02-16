# css-word-spacing

Functional CSS for word-spacing

## Filesize

| File | Size |
|------|------|
| `dist/word-spacing.css` | 609 bytes |
| `dist/word-spacing.min.css` | 433 bytes (146 Gzipped) |

## Install

```sh
npm install css-word-spacing
```

## Usage

### Import

```css
@import "css-word-spacing";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-word-spacing/dist/word-spacing.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-word-spacing/dist/word-spacing.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ws1` | `word-spacing: .3em;` |
| `.ws2` | `word-spacing: -.43em;` |
| `.ws-normal` | `word-spacing: normal;` |
| `.ws1-s` | `word-spacing: .3em;` |
| `.ws2-s` | `word-spacing: -.43em;` |
| `.ws-normal-s` | `word-spacing: normal;` |
| `.ws1-m` | `word-spacing: .3em;` |
| `.ws2-m` | `word-spacing: -.43em;` |
| `.ws-normal-m` | `word-spacing: normal;` |
| `.ws1-l` | `word-spacing: .3em;` |
| `.ws2-l` | `word-spacing: -.43em;` |
| `.ws-normal-l` | `word-spacing: normal;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ws1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/word-spacing.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/word-spacing.css` — formatted
- `dist/word-spacing.min.css` — minified

## License

MIT
