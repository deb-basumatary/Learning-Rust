# Cargo
Rust's package manager and build system. Most Rustaceans use this tool to manage their Rust projects because Cargo handles a lot of tasks for you, such as building your code, downloading the libraries your code depends on, and building those libraries.

### toml
TOML (Tom’s Obvious, Minimal Language) format, which is Cargo’s configuration format.

The first line, [package], is a section heading that indicates that the following statements are configuring a package. As we add more information to this file, we’ll add other sections.

The next three lines set the configuration information Cargo needs to compile your program: the name, the version, and the edition of Rust to use. We’ll talk about the edition key in Appendix E.

The last line, [dependencies], is the start of a section for you to list any of your project’s dependencies. In Rust, packages of code are referred to as crates. 

### Create a new Rust Project
```sh
$ cargo new <project-name>
```

# Build
This will build a executable for our project and output will be stored in target/debug/. This is a debug build not a production ready optimized.
```sh
$ cargo build
```

We can use to check if our code compiles without creating a executable. This is often faster than Build
```sh
$ cargo check
```
## Release Build
Use the following when the code is finally ready and you want optimzed production ready code. The output will be in target/release
```sh
$ cargo build --release
```
