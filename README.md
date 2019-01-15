# FlatBuffers flatc API for Rust [![crates.io](https://meritbadge.herokuapp.com/flatc-rust)](https://crates.io/crates/flatc-rust) [![Documentation](https://docs.rs/flatc-rust/badge.svg)](https://docs.rs/flatc-rust) [![Build Status](https://travis-ci.org/frol/flatc-rust.svg?branch=master)](https://travis-ci.org/frol/flatc-rust)

This crate provides a programmatical way to invoke `flatc` command (e.g. from
`build.rs`) to generate Rust (or, in fact, any other language) helpers to work
with [FlatBuffers](https://google.github.io/flatbuffers).

NOTE: You will still need
[`flatc` utility](https://google.github.io/flatbuffers/flatbuffers_guide_using_schema_compiler.html)
version [1.10.0+](https://github.com/google/flatbuffers/releases/tag/v1.10.0) installed (there are
[windows binary releases](https://github.com/google/flatbuffers/releases), `flatbuffers` packages
for [conda](https://anaconda.org/conda-forge/flatbuffers) [Windows, Linux, MacOS],
[Arch Linux](https://www.archlinux.org/packages/community/x86_64/flatbuffers/)).

## Usage and Examples

Please, refer to the [documentation](https://docs.rs/flatc-rust#examples) for usage instructions
and examples.

## Acknowledgements

The design of the API was inspired by
[protoc-rust](https://github.com/stepancheg/rust-protobuf/tree/master/protoc-rust),
[protoc](https://github.com/stepancheg/rust-protobuf/tree/master/protoc), and
[capnpc](https://github.com/capnproto/capnproto-rust/tree/master/capnpc).

## License

This project is licensed under either of

* Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0))
* MIT license ([LICENSE-MIT](LICENSE-MIT) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))

at your option.
