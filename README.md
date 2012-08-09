# urlparse2

[![Travis CI](https://secure.travis-ci.org/berkerpeksag/urlparse2.png)](http://travis-ci.org/berkerpeksag/urlparse2)

urlparse2 is a tiny wrapper for the Python module [urlparse](http://docs.python.org/library/urlparse.html).

## Installation

To install urlparse2, simply:

```bash
$ pip install urlparse2
```

## Usage

```py
>>> from urlparse2 import Url
>>> url = Url('http://www.mozilla.org/en-US/')
>>> print url
http://www.mozilla.org/en-US/
>>> print url.scheme
http
>>> url.scheme = 'https'
>>> print url
https://www.mozilla.org/en-US/
```

## License

All files that are part of this project are covered by the following license, except where explicitly noted.

> This Source Code Form is subject to the terms of the Mozilla Public
> License, v. 2.0. If a copy of the MPL was not distributed with this
> file, You can obtain one at http://mozilla.org/MPL/2.0/.
