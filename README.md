# node-xhrstub #

node-xhrstub is a wrapper for the built-in http client to emulate the
browser XMLHttpRequest object.

This can be used with JS designed for browsers to improve reuse of code and
allow the use of existing libraries.

Note: This library currently conforms to [XMLHttpRequest 1](http://www.w3.org/TR/XMLHttpRequest/).

## Usage ##

Here's how to include the module in your project and use as the browser-based
XHR object.

	var XMLHttpRequest = require("xmlhttprequest").XMLHttpRequest;
	var xhr = new XMLHttpRequest();

## License ##

MIT license. See LICENSE for full details.

## Supports ##

* Async and synchronous requests
* GET, POST, PUT, and DELETE requests
* All spec methods (open, send, abort, getRequestHeader,
  getAllRequestHeaders, event methods)
* Requests to all domains
* XML parsing

## Acknowledgements ##

This is a fork of [node-XMLHttpRequest](https://github.com/driverdan/node-XMLHttpRequest). 
