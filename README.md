# pretty.rs

Wadler-style pretty-printing combinators in Rust

[![build status](https://api.travis-ci.org/epsilonz/pretty.rs.svg?branch=master)](https://travis-ci.org/epsilonz/pretty.rs)

## Synopsis

This library is based on Larsen's SML translation (https://github.com/kfl/wpp) of Wadler's Haskell pretty printer (http://homepages.inf.ed.ac.uk/wadler/papers/prettier/prettier.pdf).

## Documentation

See the generated API documentation [here](http://www.rust-ci.org/epsilonz/pretty.rs/doc/pretty/).

## Requirements

1.   [Rust](http://www.rust-lang.org/)
2.   [Cargo](http://crates.io/)

You can install both with the following:

```
$ curl -s https://static.rust-lang.org/rustup.sh | sudo sh
```

See [Installing Rust](http://doc.rust-lang.org/guide.html#installing-rust) for further details.

## Usage

```
$ cargo build       ## build library and binary
$ cargo run         ## run the example (pretty trees)
```
