# Nimiq Style Framework

The Nimiq CSS framework, defining UI look and feel: colors, fonts, sizes.

**Please refer to the [demo page](demo.html)**
for examples and in-depth explanations of available UI components, how they look like, and how to use them.

## Add Nimiq Style to your project

The style framework consists of two parts, the CSS definitions and
the fonts, available via Google Fonts.

### Add the CSS

#### Via NPM
```bash
yarn add @nimiq/style
// or
npm install @nimiq/style
```

And then import the style into your CSS file:

```css
@import 'node_modules/@nimiq/style/nimiq-style.min.css';
```

#### Via a CDN

Link to the CSS directly in your HTML:

```html
<link href="https://cdn.jsdelivr.net/npm/@nimiq/style@v0/nimiq-style.min.css" rel="stylesheet">
```

## Add the Official Fonts

To use Nimiq's main font "Muli", include it from Google Fonts:

```html
<link href="https://fonts.googleapis.com/css?family=Muli:400,600,700" rel="stylesheet">
```

The Nimiq style uses the monospace font "Fira Mono" to display account numbers.
Include the required subset from Google Fonts:

```html
<link href="https://fonts.googleapis.com/css?family=Fira+Mono&text=0123456789ABCDEFGHJKLMNPQRSTUVXY" rel="stylesheet">
```
