# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

This project does not adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) yet, since it's pre-1.0.0.

[Unreleased]: https://github.com/1j01/anypalette.js/compare/v0.1.0...HEAD
## [Unreleased]
### Changed
- `AnyPalette.load` is now `AnyPalette.loadPalette`; this is so destructuring can work nicely without the function name being so generic. (And also, it has the name of the class that it loads, which is a nice bit of self-documentation. It doesn't load an `AnyPalette` (that's the namespace), it loads a `Palette`)
- `n_columns` is now `numberOfColumns`
- (Undocumented property `has_dimensions` is now `geometrySpecifiedByFile`)
- (The API is now fully camelCase.)

[0.1.0]: https://github.com/1j01/anypalette.js/compare/c74f0d93543c4f52ee7c1fd6e6c9201d47b0df33...v0.1.0
## [0.1.0] - 2018-09-21
### Added
- Initial release.