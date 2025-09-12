# Rust Sandbox

A couple projects written in Rust to explore its capabilities.

## Description

- mini_grep: simple command line tool to imitate grep.
- hello_web_server: a simple web server that says "hello".

## Getting Started

### Dependencies

* Rust: [https://go.dev/doc/install](https://www.rust-lang.org/tools/install)

### Executing mini_grep program

1. Check that you have Rust installed
```
rustc --version
```
2. Change directory into module
```
cd mini_grep
```
3. Run code. The command line takes in two arguments. First being the string to search for. The second being the name of file to search.
```
cargo run -- body poem.txt
```

### Executing hello_web_server program

1. Check that you have Rust installed
```
rustc --version
```
2. Change directory into module
```
cd hello_web_server
```
3. Run code. 
```
cargo run
```
4. Open local host, 127.0.0.1:7878, in your browser.

## Authors

Moses Yoo, juyoung.m.yoo at gmail dot com.

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the BSD 3-Clause license. See the LICENSE.md file for details.

## Acknowledgments

These projects were inspired by the Rust Programming Language book: https://doc.rust-lang.org/book/ch12-00-an-io-project.html
