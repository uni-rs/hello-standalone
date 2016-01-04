# Uni.rs hello world standalone example [![Build Status](https://travis-ci.org/uni-rs/hello-standalone.svg)](https://travis-ci.org/uni-rs/hello-standalone)

This project is an example of project structure that uses the
[Uni.rs](https://github.com/uni-rs/uni.rs) unikernel. This example is the hello
example taken from the Uni.rs repository, but with an independent
infrastructure.

## Building the example

As Uni.rs only supports xen for now, this example will build a xen compatible
binary. The project can be build using cargo and supports x86 and x86_64.

```
# x86 build
$ cargo build --release target=i686-unknown-uni.json

# x86_64 build
$ cargo build --release target=x86_64-unknown-uni.json
```
