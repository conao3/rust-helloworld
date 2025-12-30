# rust-helloworld

A minimal Rust "Hello, World!" example project.

## Overview

This repository contains a straightforward Rust program that prints "Hello, world!" to the console. It serves as a starting point for learning Rust or as a template for new projects.

## Requirements

- [Rust](https://www.rust-lang.org/tools/install) (1.31 or later, 2018 edition)

## Building

```bash
cargo build
```

For an optimized release build:

```bash
cargo build --release
```

## Running

```bash
cargo run
```

Expected output:

```
Hello, world!
```

## Project Structure

```
rust-helloworld/
├── Cargo.toml    # Project manifest
├── Cargo.lock    # Dependency lock file
├── src/
│   └── main.rs   # Entry point
├── LICENSE       # Apache 2.0 license
└── README.md
```

## License

Apache License 2.0

Copyright (c) Naoya Yamashita

See [LICENSE](LICENSE) for details.

## Author

[Naoya Yamashita](https://github.com/conao3)
