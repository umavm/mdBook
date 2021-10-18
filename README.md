# mdBook
mdBook is a utility to create modern online books from Markdown files.

# What does it look like?
mdBook is a command line tool and Rust crate to create books with Markdown. The output resembles tools like Gitbook, and is ideal for creating product or API documentation, tutorials, course materials or anything that requires a clean, easily navigable and customizable presentation. mdBook is written in Rust; its performance and simplicity made it ideal for use as a tool to publish directly to hosted websites such as GitHub Pages via automation. This guide, in fact, serves as both the mdBook documentation and a fine example of what mdBook produces.
mdBook includes built in support for both preprocessing your Markdown and alternative renderers for producing formats other than HTML. These facilities also enable other functionality such as validation. Searching Rust's crates.io is a great way to discover more extensions.

# Getting Started

## Installation

### Linux/MacOS
If you’re using Linux or macOS, open a terminal and enter the following command
1. Install Rustup and cargo by running this command in the terminal.(Note: You may need to reopen the terminal after this command executes.)
```c
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
 ```
 2. Install the mdbook CLI from cargo
```c
 cargo install mdbook
```
3. Check version of mdbook installed to verify the installation was successful
```c
cargo -V
```
On macOS, you can get a C compiler by running:
```c
$ xcode-select --install
```

### Windows
1. Install rustup and cargo go to -
```c
https://www.rust-lang.org/tools/install
```
2. To use cargo, you may need to have C++ build tools. If you don't have it installed, there are two options, choose either one.

a. GNU C Compiler:
Install it using the following commands
```c
rustup toolchain install stable-x86_64-pc-windows-gnu rustup default stable-x86_64-pc-windows-gnu
```
b. Visual Studio C++ Build Tools: Install C++ Build tools from this link
```c
https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019
```
3.Install the mdbook CLI from cargo
```c
cargo install mdbook
```
4. Check version of mdbook installed to verify the installation is successful
```c
cargo -V
```
