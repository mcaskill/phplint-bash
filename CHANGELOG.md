# Release Notes for `bin/phplint`

## 0.2.0 - 2018-06-08

Refactored script with argument parsing and expanded `find | xargs | grep` to detect missing search paths, early exit conditions, verbose information, and support for a quiet mode.

### Added

- `-q|--quiet` options to silence standard output
- `-p|--progress` options to output progress of run
- `verbose()` function and `-v|--verbose` options to output additional information
- `join()` function to concatenate list of search paths
- `path_count()` function to resolve singular or plural form message
- `file_count()` function to resolve singular or plural form message
- Initialized variables and argument parser
- Early exit conditions at various stages
- Normal and verbose information at various stages

### Changed

- Expanded `find | xargs | grep` to handle missing paths
- Documented functions

## 0.1.0 - 2018-06-08

Initial release; based on [locomotivemtl/charcoal-app](https://github.com/locomotivemtl/charcoal-app#e90a87e).

### Added

- `find […] | xargs […] | grep […]` commands from locomotivemtl/charcoal-app
- `[<dirs>]...` arguments to customize search paths on `find`; defaults to `src tests` directories
- `show_usage()` function, `-h|--help` options, and conditional statement to output information
- `show_header()` function, `-V|--version` options, and conditional statement to output information
