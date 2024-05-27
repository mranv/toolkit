
# Rust based Toolkit for red team

This repository contains a collection of tools and utilities written in Rust for offensive security and red teaming operations. These tools are designed to assist penetration testers, security researchers, and red teamers in various tasks during engagements or security assessments.

## Tools

### Injections

This module provides functionalities for injecting shellcode or executing code in the context of other processes. It supports various injection techniques, such as process hollowing, remote thread creation, and more.

### Windows Services

A utility for interacting with Windows services, including enumerating, installing, starting, stopping, and removing services. This can be useful for persistence or privilege escalation purposes.

### PEParser

A tool for parsing and analyzing Portable Executable (PE) files. It can be used to extract information from executables, such as imported functions, exported functions, and sections.

## Usage

Each tool or module has its own set of instructions and options, which can be accessed by running the tool with the `--help` flag. For example:

```
$ cargo run --bin main -- --help
```

## Building

To build the project, ensure you have Rust and Cargo installed, then run:

```
$ cargo build --release
```

The compiled binaries will be located in the `target/release` directory.

## Contributing

Contributions to this repository are welcome! If you find any issues or have ideas for new tools or improvements, please open an issue or submit a pull request.

## Disclaimer

These tools are provided for educational and research purposes only. They should be used only on systems or networks where you have explicit permission to perform security assessments. Any unauthorized or unlawful use is strictly prohibited.
