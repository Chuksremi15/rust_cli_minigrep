# minigrep

A command-line tool for searching for patterns in files, implemented in Rust. This project is a simplified version of the Unix `grep` command, built as an exercise while learning Rust.

## Features

- Search for a string within a file.
- Case-sensitive search by default.
- Case-insensitive search via an environment variable.

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) installed on your system.

## Building the Project

Navigate to the root directory of the project in your terminal and run:

```bash
cargo build
# Building the Project
```

### Running the Project

```bash
target\debug\minigrep.exe <query> <file_path>
```

### Case-Insensitive Search

```bash
IGNORE_CASE=1 target/debug/minigrep "rust" example.txt
```
