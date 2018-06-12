# PHPLint

A bash wrapper around `php -l` to recursively perform syntax checks on PHP files with several processes at once.

## Installation

```console
$ composer require mcaskill/phplint-bash
```

## License

This is licensed under MIT.

---

> `-l, --syntax-check`
> 
> Provides a convenient way to perform only a syntax check on the given PHP code. On success, the text _No syntax errors detected in <filename>_ is written to standard output and the shell return code is `0`. On failure, the text _Errors parsing <filename>_ in addition to the internal parser error message is written to standard output and the shell return code is set to `-1`.
> 
> This option won't find fatal errors (like undefined functions). Use the `-f` to test for fatal errors too.

— [PHP command line options](http://php.net/manual/en/features.commandline.options.php)
