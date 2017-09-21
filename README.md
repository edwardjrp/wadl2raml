# WADL2RAML

This is a simple WADL to RAML 1.0 converter. Written for my own project use.

It currently is *very* alpha in quality and not general purpose. However,
since it does run on a couple of the WADL files I needed to convert, I've found 
it useful for my own use and am releasing it as-is.

## Installation

1. Ruby: you need to have a functional installation of Ruby
2. Dependencies: run `bundle install` in this directory.
3. Put the file `bin/wadl2raml` in your path.

## Usage

Running:

```sh
wadl2raml some.wadl some-other.wadl
```

will produce the files:

* `some.raml`
* `some-other.raml`
