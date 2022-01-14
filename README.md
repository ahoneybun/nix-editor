# Nix-Editor
A command line utility for modifying NixOS configuration values.

## Usage with Nix Flakes
```
nix run github:vlinkz/nix-editor -- --help
```

```
USAGE:
    nix-editor [OPTIONS] <FILE> <ATTRIBUTE>

ARGS:
    <FILE>         Configuration file to read
    <ATTRIBUTE>    Nix configuration option arribute

OPTIONS:
    -d, --deref              Dereference the value of the query
    -h, --help               Print help information
    -o, --output <OUTPUT>    Output file for modified config or read value
    -v, --val <VAL>          Value to write
    -V, --version            Print version information
```