# Comprehensive Rust 🦀

## Intro

### Installation

#### Installing rustup on Arch Linux

```bash
$ sudo pacman -S rustup
```

> Note that `rustup self update` will **not** work when installed this way, this package needs to be updated by pacman.

> The `rustup` package does **not** install a toolchain by default. In order to install the toolchain, you need to tell rustup which version to use: `stable` or `nightly`.

Example:

```bash
$ rustup default stable
```

### The Rust Ecosystem

- `rustc`: the Rust compiler
- `cargo`: the Rust dependency manager and build tool
- `rustup`: the Rust toolchain installer and updater
- `cargo new xxx` to create a new xxx/ directory
- `cargo run`: build and run your binary
- `cargo check` to quickly check your project for errors, and `cargo build` to compile it without running it
- `cargo build --release` to produce an optimized release build
- add dependencies for your project by editing `Cargo.toml`. When you run `cargo` commands, it will automatically download and compile missing dependencies for you

## Day 1

- Basic Rust syntax: variables, scalar(integer,float,bool,char) and compound(tuple,array) types, enums, structs, references, functions, and methods
- Memory management: stack vs heap, manual memory management, scope-based memory management, and garbage collection
- Ownership: move semantics, copying and cloning, borrowing, and lifetimes

No parenthesis around expression

### Why Rust?

- Compile time memory safety
- Lack of undefined runtime behavior
- Modern language features

### Scalar Types

