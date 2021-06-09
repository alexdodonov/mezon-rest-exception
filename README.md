# REST Exception [![Build Status](https://travis-ci.com/alexdodonov/mezon-rest-exception.svg?branch=master)](https://travis-ci.com/alexdodonov/mezon-rest-exception) [![codecov](https://codecov.io/gh/alexdodonov/mezon-rest-exception/branch/master/graph/badge.svg)](https://codecov.io/gh/alexdodonov/mezon-rest-exception)

## Installation

Just type

```
composer require mezon/rest-exception
```

# Learn more

More information can be found here:

[Twitter](https://twitter.com/mezonphp)

[dev.to](https://dev.to/alexdodonov)

## Usage

To use this class is very simple thing:

```PHP
throw(new \Mezon\Rest\Exception(
	"", // message of the exception, like in the standard Exception class
	-1, // code of the exception, like in the standard Exception class
	200, // HTTP code of the request
	"<p>Warning!" // HTTP request body
));
```
