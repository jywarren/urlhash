# urlhash
A simple library for reading and writing parameters to the URL hash.


## Installation

You can install with `npm install urlhash` and include with `var urlhash = require('urlhash')`.

For basic use in the browser, you can simply include `urlHash.js` and use `urlhash().getUrlHashParameter(param)` as below.


## Usage

`urlhash.getUrlHashParameter(param)`

returns the value of the named url hash parameter, so `bar` from `example.com#foo=bar`

`urlhash.getUrlHashParameters()`

returns all url hash parameters in an object, so `{foo: 'bar', bibim: 'bap'}` from `example.com#foo=bar&bibim=bap`

`urlhash.setUrlHashParameter(param, value)`

sets the value of the named url hash parameter, so `example.com#foo=bar` from `setUrlHashParameter('foo', 'bar')`

`urlhash.setUrlHashParameters(params)`

sets all url hash parameters in a passed object, so `example.com#foo=bar&bibim=bap` from `{foo: 'bar', bibim: 'bap'}`
