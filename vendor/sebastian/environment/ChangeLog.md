# Changes in sebastianbergmann/environment

All notable changes in `sebastianbergmann/environment` are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [3.0.2] - 2017-04-21

### Fixed

* Fixed [#17](https://github.com/sebastianbergmann/environment/issues/17): `Uncaught TypeError: trim() expects parameter 1 to be string, boolean given`

## [3.0.1] - 2017-04-21

### Fixed

* Fixed inverted logic in `Runtime::discardsComments()`

## [3.0.0] - 2017-04-21

### Added

* Implemented `Runtime::discardsComments()` for querying whether the PHP runtime discards annotations

### Removed

* This component is no longer supported on PHP 5.6

[3.0.2]: https://github.com/sebastianbergmann/phpunit/compare/3.0.1...3.0.2
[3.0.1]: https://github.com/sebastianbergmann/phpunit/compare/3.0.0...3.0.1
[3.0.0]: https://github.com/sebastianbergmann/phpunit/compare/2.0...3.0.0

