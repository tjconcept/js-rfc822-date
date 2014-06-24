# rfc822-date

Convert a Date object to a rfc-822 date string

## RFC 1123

RFC 1123 is an update to RFC 822 which specifies that the year MUST be
4 digits. As this library has always used 4 digits for the year, it
is compatible with both.

## usage

	var rfc822Date = require('rfc822-date');

	console.log(rfc822Date(new Date())); // 'Mon, 13 Sep 2013 14:27:00 +0200'

## License

[MIT](http://opensource.org/licenses/MIT) © [Thomas Jensen](http://tjconcept.dk)