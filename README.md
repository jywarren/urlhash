# urlhash
A simple library for reading and writing parameters to the URL hash.

## Usage

`getUrlHashParameter(param)` - returns the value of the named url hash parameter, so `bar` from `example.com#foo=bar`

`getUrlHashParameters()` - returns all url hash parameters in an object, so `{foo: 'bar', bibim: 'bap'}` from `example.com#foo=bar&bibim=bap`

`setUrlHashParameter(param, value)` - sets the value of the named url hash parameter, so `example.com#foo=bar` from `setUrlHashParameter('foo', 'bar')`

`setUrlHashParameters(params)` - sets all url hash parameters in a passed object, so `example.com#foo=bar&bibim=bap` from `{foo: 'bar', bibim: 'bap'}`
