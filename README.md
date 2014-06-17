scapegoat
=========

A small library providing utility methods to 'escape' and 'unescape' HTML entities

## Installation

    npm install scapegoat --save

## Usage

    var scapegoat = require('scapegoat'),
        escape = scapegoat.escape,
        unescape = scapegoat.unescape;

    var html = '<h1>Hello World</h1>',
        escaped = escape(html),
        unescaped = unescape(escaped);

    console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

    npm test

## Contributing

    IN lieu of a formal styleguide, take care to maintain the existing coding style.
    Add unit tests for any or changed functionlity. Lint and test your code.

## Release History
* 0.1.0 Initial release

## Copyright
    http://quickleft.com/blog/creating-and-publish-a-node-js-module
    I just want to practice how to create and publish a node module.
