specialchar
=========

A small library providing utility methods to `escape` and `unescape` HTML entities

## Installation

  npm install specialchar --save

## Usage

  var specialchar = require('specialchar')
      escape = specialchar.escape,
      unescape = specialchar.unescape;

  var html = '<h1>Hello World</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);

## Tests

  npm test


## Release History

* 0.0.1 Initial release