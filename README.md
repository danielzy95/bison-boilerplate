# Bison Boilerplate

A basic bison boilerplate.

## Getting Started

### Requirements

- [g++](https://gcc.gnu.org/)
- flex
- bison
- [make](https://www.gnu.org/software/make/)

### Build

```
    $ make
```

### Build & Run

```
    $ make run
```

### Clean

```
    $ make clean
```

## .gitignore Directories

- bin
- obj
- src/flex
- src/bison

`src/flex` and `src/bison` will only contain the source files generated by flex and bison so do not add any development file there.

## Caveats

Relative includes (`#include "./foo.h"`) in the `*.l` and `*.y` files are relative to the `src/flex` and `src/bison` folders respectively.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/danielzy95/bison-boilerplate/blob/master/LICENSE) file for details.