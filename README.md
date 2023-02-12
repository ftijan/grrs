# Rust Command Line App Example

`grrs` is a very simple `grep` clone, based on the tutorial found here: [Rust CLI E-book](https://rust-cli.github.io/book/tutorial/index.html).

Topics covered:
- Rust APIs
- Usage of various `Cargo` package libraries
- Testing

Quick start:
- Install dependencies with:  `cargo install --path .`
- Invoke app parameters help with `cargo`: `cargo run -- --help`
- Run with search parameters: `cargo run -- <search_param> <file_path>`
  - Example: `cargo run -- main src/main.rs`