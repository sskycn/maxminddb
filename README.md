# MaxMind DB Reader for Go #

[![Build Status](https://travis-ci.org/sskycn/maxminddb.svg?branch=master)](https://travis-ci.org/sskycn/maxminddb)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/4j2f9oep8nnfrmov/branch/master?svg=true)](https://ci.appveyor.com/project/sskycn/maxminddb/branch/master)
[![GoDoc](https://godoc.org/github.com/sskycn/maxminddb?status.svg)](https://godoc.org/github.com/sskycn/maxminddb)

This is a Go reader for the MaxMind DB format. Although this can be used to
read [GeoLite2](http://dev.maxmind.com/geoip/geoip2/geolite2/) and
[GeoIP2](https://www.maxmind.com/en/geoip2-databases) databases,
[geoip2](https://github.com/sskycn/geoip2-golang) provides a higher-level
API for doing so.

This is not an official MaxMind API.

## Installation ##

```
go get github.com/sskycn/maxminddb
```

## Usage ##

[See GoDoc](http://godoc.org/github.com/sskycn/maxminddb) for
documentation and examples.

## Examples ##

See [GoDoc](http://godoc.org/github.com/sskycn/maxminddb) or
`example_test.go` for examples.

## Contributing ##

Contributions welcome! Please fork the repository and open a pull request
with your changes.

## License ##

This is free software, licensed under the ISC License.
