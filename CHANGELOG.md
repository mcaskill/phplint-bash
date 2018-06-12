# Release Notes for `bin/phplint`

## 0.1.0 - 2018-06-08

Initial release; based on [locomotivemtl/charcoal-app](https://github.com/locomotivemtl/charcoal-app#e90a87e).

### Added

- `find […] | xargs […] | grep […]` commands from locomotivemtl/charcoal-app
- `[<dirs>]...` arguments to customize search paths on `find`; defaults to `src tests` directories
- `show_usage()` function, `-h|--help` options, and conditional statement to output information
- `show_header()` function, `-V|--version` options, and conditional statement to output information
