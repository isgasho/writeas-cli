Change log
==========

## [1.0](https://github.com/writeas/writeas-cli/compare/v0.4...v1.0) - 2017-11-18

### Changed

* All logging and errors go to stderr, not stdout (#11)
* Verbose logging requires `-v` or `--verbose` flag
* Executable now lives in `cmd/` directory

### Fixed

* All errors exit with status 1
* `cli` library deprecation (#8)

## [0.4](https://github.com/writeas/writeas-cli/compare/v0.3...v0.4) - 2015-12-10

### Added

* `--font [value]` option for creating and updating posts

### Changed

* Use SSL for all requests

### Fixed

* `--code` flag not working on `writeas --code` command

## [0.3](https://github.com/writeas/writeas-cli/compare/v0.2...v0.3) - 2015-09-08

### Added

* Compose new posts in default text editor with `writeas new`
* Automatically copy URL to clipboard when publishing a new post
* Status messages when updating, deleting, or fetching posts

### Changed

* More helpful help on `writeas add` command
* More error messages when something goes wrong

### Fixed

* Error on `writeas list` when there are no saved posts
* User-Agent header missing on most requests to backend

## [0.2](https://github.com/writeas/writeas-cli/compare/v0.1.1...v0.2) - 2015-05-11

### Added

* Update posts with `writeas update`
* Add posts locally with `writeas add`

### Changed

* Post font is now _monospace_

## [0.1.1](https://github.com/writeas/writeas-cli/compare/v0.1...v0.1.1) - 2015-04-12

### Fixed

* Post fetching

## 0.1 - 2015-04-11

### Added

* Initial release
