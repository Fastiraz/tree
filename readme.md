<div align='center'>
  <h1><code>tree</code></h1>
  <p>A simple Rust script to list the contents of directories and their nested subdirectories with custom options.</p>
</div>

---

## Description

The `tree` command is a simple Rust script for listing the contents of directories and their nested subdirectories, following certain user-specified options such as limiting the number of entries, filtering by file type or name patterns, displaying full paths, and more.

## Setup

### Requirements

This project requires Rust 1.x.x and Cargo to be installed on your system. To check if you have Rust installed, run `rustc --version` in the terminal. If not installed, please follow [the official installation guide](https://www.rust-lang.org/tools/install).

### Download

Clone this repository using:
```bash
git clone https://github.com/Fastiraz/tree.git
```

### Build

Build the project using:
```bash
cargo b --release
```

This will create a binary named `tree-target/debug/tree`. You can use this binary directly or build for release mode by using `cargo b --release` instead.

## Features

* List directories and their contents recursively with custom options.
* Filter the displayed entries based on file types, name patterns, and depth levels.
* Display full paths of files and directories in the output.
* Colored directories and hidden files.

## Upcoming features
- [x] Rewrite tree in Rust (for performance and security improvements)
- [x] Add `--hidden` option to show/hide hidden files and directories
- [ ] Add `--way` option to find path to a specified file name
- [ ] Add `--size` option to display file sizes in the output

## Credits

Special thanks to:
|dev|repo|
|-|-|
|`kddeisz`|https://github.com/kddeisz/tree/blob/master/tree.rs|
|`fairingrey`|https://github.com/fairingrey/tree|