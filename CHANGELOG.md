# Changelog
All notable changes to this project since v3.50 will be documented in this
file.

The format is based on [Keep a
Changelog](https://keepachangelog.com/en/1.0.0/), version strings comprise
a major and minor version only.

## [Unreleased]

### Fixed

- Fix optional arguments of `\frame` in `beamerarticle` (see #509)
- Compact glue settings for lists
- Turn off font substitution for `unicode-math` package (see #508)

## [v3.54]

## Changed

- Add the instructions of `proof begin` and `proof end` template
- Patch for `paralist` package

### Fixed

- Wrong frame number by `noframenumbering` option (see #450)
- Missing `nokeywords` option in the article mode
- Vertical glues by `allowframebreak` option (see #325)
- Typos and bad boxes in the documentation (see #491, #504 and #505)
- Revert the addition of `\input` and `\include`

## [v3.53]

### Fixed

- Behavior of `bg` key

## [v3.52]

### Fixed
- Behaviour of `\inst` (see #489)
- Incorrect shadows when using DVI routes (see #492)

## [v3.51]

### Changed
- Add `\include` and `\input` to commands respected in 'skipping' mode
- Dynamically calculate note page size (see #487)

### Fixed
- Properly set space in rounded boxes
- Enable transparency in shadows (see #466)
- Restore `\secname` in `\sectionentry`
- Apply color correctly to page number (see #468)
- Support for `noxcolor` with `beamerarticle` (see #483)
- Treatment of mixed overlay/alert specifications

[Unreleased]: https://github.com/josephwright/beamer/compare/v3.54...HEAD
[v3.54]: https://github.com/josephwright/beamer/compare/v3.53...v3.54
[v3.53]: https://github.com/josephwright/beamer/compare/v3.52...v3.53
[v3.52]: https://github.com/josephwright/beamer/compare/v3.51...v3.52
[v3.51]: https://github.com/josephwright/beamer/compare/v3.50...v3.51
