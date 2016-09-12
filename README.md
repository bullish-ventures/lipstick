<h3 align="center">
  <br>
  <a href="https://github.com/bullish-ventures/lipstick">
    <img src="src/images/logo.png" alt="Lipstick logo">
    <p>Lipstick</p>
</a>
</h3>
<br>
<p align="center">Anything can be beautiful with a little lipstick.</p>
<br>

---

### A micro, responsive CSS framework written in LESS that will turn heads.

Lightweight and minimal. Sane defaults allow for very few overrides and quick scaffolding. Comes with some sexy default themes and common components.

[![Build Status](https://travis-ci.org/bullish-ventures/lipstick.svg?branch=master)](https://travis-ci.org/bullishventures/lipstick)

## Installation

Getting started is easy, simply install Lipstick using [NPM](https://www.npmjs.com/):

    npm install --save lipstickless

### Vanilla

If you aren't using any build tools you can simply copy the CSS files into your project.

### Using the CDN

Minified and unminified versions are available over CDN so you can simply include them in your HTML if needed.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lipstick</title>
    <link rel="stylesheet" href="//unpkg.com/lipstickless@^0.1.0/dist/css/lipstick.css">
    <!-- Minified Version -->
    <!-- <link rel="stylesheet" href="//unpkg.com/lipstickless@^0.1.0/dist/css/lipstick.min.css"> -->
</head>
<body>
    
</body>
</html>
```

### LESS

If you are building your own LESS files and want to include the Lipstick less files in your build simply reference them in your main less file like so:

```less
@import "path/to/node_modules/lipstickless/src/less/main";
```

Alternatively, you can also cherry pick specific files by referencing them individually instead of the `main.less` file.

### Webpack

TODO

## Usage

Once you have the latest version of Lipstick installed head on over and [view the docs](http://bullish.io/opensource/lipstick).

## Support
IE8+ and all other modern browsers

## License
[MIT](./LICENSE)

---

Borrowed heavily from [Base](http://getbase.org) v2 by [Matthew Hartman](http://twitter.com/matthewhartmans), so massive :heart:  to him.

Lipstick icon based off of one created by Cezary Rudaś.
