# kikozip

> A simple CLI tool for extracting zip archives

## Installation

```bash
cargo install kikozip --git https://github.com/AnimeshRy/kikozip
```

## Usage

```
Tool for extracting zip archives

Usage: kikozip [OPTIONS] <FILE>

Arguments:
  <FILE>  Path to the zip archive

Options:
  -o, --out <OUT>            Output location. Extracts to a new folder in the current directory if none given
  -p, --password <PASSWORD>  Password if the archive is encrypted
  -e, --encoding <ENCODING>  Codec to be used for filename encoding (default: UTF-8)
  -s, --silent               Make output less verbose
  -h, --help                 Print help
  -V, --version              Print version
```
