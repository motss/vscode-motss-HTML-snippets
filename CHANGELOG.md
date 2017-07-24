# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2017-07-24

### Added

- Added 6 more snippets that might come in handy:
  - __hib__ - HTML Import element from `bower_components`.
  - __hid__ - HTML Import element from `bower_components` but element's directory and filename do not share the same name. E.g. `<link rel="import" href="../bower_components/x-elements/custom-x-element.html">`
  - __sf__ - Static function.
  - __sfp__ - Static function with parameters.
  - __sfg__ - Static get function.
  - __gf__ - Get function.

## [0.2.3] - 2017-03-12

### Changed

- Typo in the `whenDefined` code snippet.

## [0.2.2] - 2017-03-12

### Fixed

- Rearranged placeholder's enumeration in the snippets.

- Enforces `lf` as `EOF` even on Windows platform for consistency reason.

## [0.2.1] - 2017-03-12

### Added

- Added __pcea__ - Polymer.Element that extends native Web Components with a thin sugaring layer to make building Web Components sweet once again.

## [0.2.0] - 2017-01-24

### Added

- __ce-wd__ - Custom Element's `whenDefined` method.

### Fixed

- Fixed `Uncaught SyntaxError` when registering multiple Custom Elements.

## [0.1.5] - 2017-01-16

### Changed

- Minor update on the `repository` field in the `package.json`.

### Fixed

- Fixed whitespaces for proper indentation.

## [0.1.2] - 2017-01-16

### Changed

- Changed the location of `html.json` to `snippets/html.json`.

## [0.1.1] - 2016-12-19

### Added

- __cee-html-v1__ - Extending Custom Element v1 snippet
- __cea-html-v1__ - Autononmous Custom Element v1 snippet

[Unrelease]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.2.3...v0.3.0
[0.2.3]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.1.5...v0.2.0
[0.1.5]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.1.2...v0.1.5
[0.1.2]: https://github.com/motss/vscode-motss-HTML-snippets/compare/v0.1.1...v0.1.2
