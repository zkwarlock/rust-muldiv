# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html),
specifically the [variant used by Rust](http://doc.crates.io/manifest.html#the-version-field).

## [0.2.0] - 2018-05-11
### Changed
- Switch to i128/u128 and require Rust 1.26 instead of having our own 96/128
  bit integer implementation

## [0.1.1] - 2017-08-18
### Added
- README.md

### Changed
- Relicensed from LGPLv2 to MIT
- Use docs.rs for the documentation

### Fixed
- Various clippy warnings

## [0.1.0] - 2016-02-26

- Initial release of muldiv.

[Unreleased]: https://github.com/sdroege/rust-muldiv/compare/0.2.0...HEAD
[0.2.0]: https://github.com/sdroege/rust-muldiv/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/sdroege/rust-muldiv/compare/0.1.0...0.1.1