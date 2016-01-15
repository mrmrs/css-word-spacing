# css-word-spacing 0.0.6

Css module of single purpose classes for word spacing

#### Stats

230 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-word-spacing
```

#### With Git

```
git clone https://github.com/tachyons-css/css-word-spacing
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-word-spacing";
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
<link rel="stylesheet" href="path/to/module/css/css-word-spacing">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WORD SPACING
*/
.wsn { word-spacing: normal; }
.ws1 { word-spacing: 0.3em; }
.ws2 { word-spacing: -0.43em; }
/* For eliminating space between inline-block elements */
@media screen and (min-width: 48em) {
 .wsn-ns { word-spacing: normal; }
 .ws1-ns { word-spacing: 0.3em; }
 .ws2-ns { word-spacing: -0.43em; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .wsn-m { word-spacing: normal; }
 .ws1-m { word-spacing: 0.3em; }
 .ws2-m { word-spacing: -0.43em; }
}
@media screen and (min-width: 64em) {
 .wsn-l { word-spacing: normal; }
 .ws1-l { word-spacing: 0.3em; }
 .ws2-l { word-spacing: -0.43em; }
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

MIT

