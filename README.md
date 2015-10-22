## content-edit

[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][npm-url]
[![MIT License][https://img.shields.io/dub/l/vibe-d.svg]][http://isekivacenz.mit-license.org]

tools for content editable elements. Inserting html, removing html, position caret, etc...

Thanks to [tim down](https://github.com/timdown) and his [rangy module](https://github.com/timdown/rangy) as most of the code is based on his work.

``` js
var contentEdit = require('content-edit');

var el = document.getElementById("content");
contentEdit.placeCaretAtStart(el);
```

## Development

make sure you have babel installed globally to compile the `src` directory to the `lib` directory.

`npm install --global babel`

    npm run build

## Running Tests server side

**modify test.js for any tests**

    npm install
    npm test

## Running Tests client side

**modify test.js for any tests**

make sure you have webpack installed globally

`npm install webpack -g`

compile test.js to a bundle with webpack

	webpack ./test/test.js ./test/test-bundle.js

open test.html to view the tests in the browser

## License

[MIT](http://isekivacenz.mit-license.org/)