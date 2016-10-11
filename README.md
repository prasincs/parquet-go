# parquet-go

```
	./dump dump ./parquet/testdata/nation.impala.parquet
```

Library to work with Parquet file format in Go.
WARNING: totally not ready to use

## Resources


## Usage

Documentation is available via
[![GoDoc](https://godoc.org/github.com/tunelabs/parquet?status.svg)](https://godoc.org/github.com/tunelabs/parquet).


[![license](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/TuneLab/parquet-go/master/LICENSE)
[![Build Status](https://travis-ci.org/TuneLab/parquet-go.svg?branch=master)](https://travis-ci.org/TuneLab/parquet-go)


## References

- [Dremel Made simple With Parquet](https://blog.twitter.com/2013/dremel-made-simple-with-parquet)

# License
MIT - see LICENSE


So the problem is to first have a schema and then write the information and keep this information to then write them at the end of the file.


# TODO

- [ ] Support Old BitEncoding (Encoder / Decoder)
- [ ] Support DataPageV2 (Encoder / Decoder)
- [ ] Support for crc inside Page
- [ ] Support for nested levels
- [ ] Support int96
- [ ] Support LZO
