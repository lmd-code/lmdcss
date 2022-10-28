# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Default `line-height` is now `1.4`.

## [1.3.0] - 2022-10-28

### Added

- Added new variable `--lmdcss-body-size` to set the default `<body>` text size in REMs according to absolute pixel size. The media query to set the `<body>` text size on wide screens is now replaced by a query to reset the `--lmdcss-body-size` variable instead. This makes it easier to set the size of any element to the current default (by referring to the var) without having to do separate media queries.

## [1.2.2] - 2022-10-11

### Fixed

- Fixed the `picture`, `audio`, `video` and `canvas` element responsiveness.

## [1.2.1] - 2022-10-10

### Fixed

- Removed "fallback" class requirement from `meter`.
- Added `overflow:hidden` to `svg` for compatibility with older browsers.

## [1.2.0] - 2022-10-09

### Fixed

- Removed top margin from first element after `legend` (`:nth-child(2)`) inside a `fieldset`.

### Added

- Added basic `picture`, `audio`, `video`, and `canvas` styles.
- Added default `small`, `del`, `ins`, `sup`/`sub` styles.
- Added `mark` style with vars for highlight and text colour.
- Added `details` styles for newer browsers only.
- Added styles for `blockquote` inside `figure` with citation in `figcaption`.

### Changed

- Modified `pre` tag styling to plain `<pre>` and `<pre><code>` versions.
- Modified `img` tag to have basic responsiveness.
- Changed cursor type for various form elements (now uses 'default').
- Created new demo page.

## [1.1.2] - 2022-10-08

### Fixed

- Typo in `figure img` style declaration.

## [1.1.1] - 2022-10-05

### Fixed

- Flexbox `min-width: auto` and `<pre>` tag overflow bug.

## [1.1.0] - 2022-09-27

### Added

- Added `<iframe><embed><object>` styles.
- Added minified version.

### Changed

- Updated README instructions.

## 1.0.0 - 2022-09-15

### Changed

- Renamed library to 'lmdcss' (final name!) for consistency with other lmd-code projects.
- Renamed CSS `--var` name prefix to reflect new/final library name.
- Updated README instructions.

## 0.3.0 - 2022-09-04

### Changed

- Renamed library to 'modcss'.
- Renamed CSS `--var` name prefix to reflect new library name.

## 0.2.0 - 2022-06-24

### Added

- Added `<table>` styles.

### Changed

- Renamed CSS `--var` name prefix.

### Fixed

- Incorrect semantic versioning.

## 0.1.0 - 2022-06-22

### Added

- First public release.

[Unreleased]: https://github.com/lmd-code/lmdcss/compare/v1.3.0...HEAD
[1.3.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.3.0
[1.2.2]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.2
[1.2.1]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.1
[1.2.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.0
[1.1.2]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.2
[1.1.1]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.1
[1.1.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.0
