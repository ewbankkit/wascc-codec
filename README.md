[![crates.io](https://img.shields.io/crates/v/wascc-codec.svg)](https://crates.io/crates/wascc-codec)&nbsp;
![travis](https://travis-ci.org/wascc/wascc-codec.svg?branch=master)&nbsp;
![license](https://img.shields.io/crates/l/wascc-codec.svg)&nbsp;
[![documentation](https://docs.rs/wascc-codec/badge.svg)](https://docs.rs/wascc-codec)

# waSCC Codec

The _WebAssembly Secure Capabilities Connector_ (waSCC) codec library contains a set of types, protobuf messages, and other primitives that are common to the host runtime, capability providers, and actor modules that are created for use with the [wascc](https://wasc.dev) host runtime, which is in turn built on top of [WebAssembly Procedure Call (waPC)](https://github.com/wapc) primitives.

This crate includes definitions for a standard set of operations supported by the default capability providers:

* **Messaging** - Message broker functionality (pub, sub, request)
* **HTTP Server** - HTTP server capability
* **HTTP Client** - HTTP client capability
* **Key-Value Store** - Standard K/V operations, including lists, sets, and atomic counters
* **Blob Store** - Cloud-native file storage capability


