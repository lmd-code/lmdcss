# Changelog

## [1.4.1] - 2022-11-25

### Fixed

- Fixed gapping after `textarea` box, caused by it being an `inline-block` element.

## [1.4.0] - 2022-11-19

### Changed

- Changed default `line-height` is now `1.5`.

### Added

- Added explicit declaration of rule `display: none` for elements with the `hidden` attribute.

## [1.3.0] - 2022-10-28

### Added

- Added new variable `--lmdcss-body-size` to set the default `<body>` text size in REMs according to absolute pixel size. The media query to set the `<body>` text size on wide screens is now replaced by a query to reset the `--lmdcss-body-size` variable instead. This makes it easier to set the size of any element to the current default (by referring to the var) without having to do separate media queries.

## [1.2.2] - 2022-10-11

### Fixed

- Fixed the `picture`, `audio`, `video` and `canvas` element responsiveness.

## [1.2.1] - 2022-10-10

### Removed

- Removed "fallback" class requirement from `meter`.

### Fixed

- Fixed `svg` display in older browsers (overflow is now hidden).

## [1.2.0] - 2022-10-09

### Changed

- Changed `pre` tag styling to plain `<pre>` and `<pre><code>` versions.
- Changed `img` tag to have basic responsiveness.
- Changed cursor type for various form elements (now uses 'default').

### Added

- Added basic `picture`, `audio`, `video`, and `canvas` styles.
- Added default `small`, `del`, `ins`, `sup`/`sub` styles.
- Added `mark` style with vars for highlight and text colour.
- Added `details` styles for newer browsers only.
- Added styles for `blockquote` inside `figure` with citation in `figcaption`.

### Fixed

- Fixed unwanted top margin on first element after `legend`.

## [1.1.2] - 2022-10-08

### Fixed

- Fixed typo in `figure img` style declaration.

## [1.1.1] - 2022-10-05

### Fixed

- Fixed flexbox `min-width: auto` and `<pre>` tag overflow bug.

## [1.1.0] - 2022-09-27

### Added

- Added `<iframe><embed><object>` styles.
- Added minified version.

## [1.0.0] - 2022-09-15

*First release under the name 'lmdcss'*

[1.4.1]: https://github.com/lmd-code/lmdcss/releases/tag/v1.4.1
[1.4.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.4.0
[1.3.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.3.0
[1.2.2]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.2
[1.2.1]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.1
[1.2.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.2.0
[1.1.2]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.2
[1.1.1]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.1
[1.1.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.1.0
[1.0.0]: https://github.com/lmd-code/lmdcss/releases/tag/v1.0.0
