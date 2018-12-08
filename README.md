# Nimiq Style Framework

The Nimiq CSS framework, defining UI look and feel: colors, fonts, sizes.

**Please refer to the [demo page](demo.html)** for examples and in-depth
explanations of available UI components, what they look like, and how to use them.

The style framework consists of two parts, the CSS definitions and
[the fonts](#use-the-official-fonts) (available via Google Fonts).

## Add Nimiq Style CSS to your project

### From NPM

```bash
yarn add @nimiq/style
# or
npm install @nimiq/style
```

Then import the style into your CSS or module files:

```css
@import 'node_modules/@nimiq/style/nimiq-style.min.css';
/* If you need the icons: */
@import 'node_modules/@nimiq/style/nimiq-style-icons.min.css';
```

### From a CDN

You can also link to the Nimiq Style CSS directly in your HTML:

```html
<link href="https://cdn.jsdelivr.net/npm/@nimiq/style@v0/nimiq-style.min.css" rel="stylesheet">
<!-- If you need the icons: -->
<link href="https://cdn.jsdelivr.net/npm/@nimiq/style@v0/nimiq-style-icons.min.css" rel="stylesheet">
```

## Use the official fonts

To use Nimiq's main font "Muli", include it from Google Fonts:

```html
<link href="https://fonts.googleapis.com/css?family=Muli:400,600,700" rel="stylesheet">
```

Nimiq also uses the monospace font "Fira Mono" to display account numbers.
Include the required subset from Google Fonts:

```html
<link href="https://fonts.googleapis.com/css?family=Fira+Mono&text=0123456789ABCDEFGHJKLMNPQRSTUVXY" rel="stylesheet">
```
