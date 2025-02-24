# Changelog
All notable changes to this project will be documented in this file.

The format is loosely based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.10.0] - 2023-06-12
- Fixed compatibility with Foundry v11, particularly for middle-mouse pan, though the solution is ugly (#49)

## [1.9.0] - 2023-04-07
- Improved (and fixed) zoom precision - will now actually center exactly on the cursor!
- Fixed incompatibility with grape_juice's isometric module (#48)
- Changed speed-based zoom calculation to be a bit more consistent (my apologies if this messes with your settings!)
- Refactored zoom code to be more readable
- Added localization files to enable translations of settings

## [1.8.6] - 2022-12-06
- Fixed reversed rotation (#43)

## [1.8.5] - 2022-12-04
- Fixed compatibility with Foundry v10.291, bug broke rotation (#42)

## [1.8.4] - 2022-10-05
- Added workaround to fix incompatibility with LockView (#31)

## [1.8.3] - 2022-09-04
- Fixed bug that prevented rotating lights and measured templates
- Changed my username from "itamarcu" to "shemetz"

## [1.8.0] - 2022-08-26
- Added "Drag resistance mode" feature with new default value ("Scaling")
- Removed "Disable Zoom Rounding" option, as it's no longer needed with Foundry v10

## [1.7.2] - 2022-07-02
- FoundryVTT V10 compatibility
- "Disable Zoom Rounding" had to be changed;  please inform me if it's worse now.

## [1.7.0] - 2022-02-25
- Split "auto-detect touchpad" setting out of pan/zoom mode, and made it false by default
- Added settings to change pad and shift values when dragging at the edge of the screen (#33)

## [1.6.10] - 2022-02-08
- Updated libWrapper shim code

## [1.6.9] - 2021-12-26
- Explicitly marked libWrapper as a dependency, and updated libWrapper shim code

## [1.6.8] - 2021-12-24
- Fixed compatibility with Foundry v9.232 (#35, #37) (thank you @caewok for the contribution!)
- Marked as compatible with Foundry v9 stable

## [1.6.5] - 2021-07-06
- Fixed minimum/maximum zoom not carrying over after refreshing ([#28](https://github.com/shemetz/ZoomPanOptions/issues/28))
- Updated default min/max zoom scale to be just like the Foundry default - i.e. `3.0`.
- Fixed rotation not working on Firefox ([#29](https://github.com/shemetz/ZoomPanOptions/issues/29))

## [1.6.3] - 2021-07-06
- Added automatic detection of touchpad movements in "Default" mode
- Added "DefaultMouse" mode which prevents this automatic detection

## [1.6.1] - 2021-05-29
- Added middle mouse pan setting
- Added changelog and license to repository

## [1.5.3] - 2021-02-05
- Added invert vertical scroll setting
- Introduced new bugs and promptly fixed them

## [1.4.0] - 2020-12-05
- Added min/max zoom override setting
- Fixed compatibility with Foundry v0.7.x

## [1.3.7] - 2020-09-17
- Added ability to use alt/option/meta key
- Fixed some minor bugs
- Improved readme
- Improved file structure

## [1.3.0] - 2020-09-16
- Integrated Canvas Scroll (thanks @akrigline!)
- Reworked to use 3 modes
- Added LibWrapper as optional dependency

## 1.0.0 - 2020-09-15
- Created the module, with initial feature set

## See also: [Unreleased]

[1.3.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.0.0...1.3.0
[1.3.7]: https://github.com/shemetz/ZoomPanOptions/compare/1.3.0...1.3.7
[1.4.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.3.7...1.4.0
[1.5.3]: https://github.com/shemetz/ZoomPanOptions/compare/1.4.0...1.5.3
[1.6.1]: https://github.com/shemetz/ZoomPanOptions/compare/1.5.3...1.6.1
[1.6.3]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.1...1.6.3
[1.6.5]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.3...1.6.5
[1.6.8]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.5...1.6.8
[1.6.9]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.8...1.6.9
[1.6.10]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.9...1.6.10
[1.7.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.6.10...1.7.0
[1.7.2]: https://github.com/shemetz/ZoomPanOptions/compare/1.7.0...1.7.2
[1.7.4]: https://github.com/shemetz/ZoomPanOptions/compare/1.7.2...1.7.4
[1.8.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.7.4...1.8.0
[1.8.3]: https://github.com/shemetz/ZoomPanOptions/compare/1.8.0...1.8.3
[1.8.4]: https://github.com/shemetz/ZoomPanOptions/compare/1.8.3...1.8.4
[1.8.5]: https://github.com/shemetz/ZoomPanOptions/compare/1.8.4...1.8.5
[1.8.6]: https://github.com/shemetz/ZoomPanOptions/compare/1.8.5...1.8.6
[1.9.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.8.6...1.9.0
[1.10.0]: https://github.com/shemetz/ZoomPanOptions/compare/1.9.0...1.10.0
[Unreleased]: https://github.com/shemetz/ZoomPanOptions/compare/1.10.0...HEAD
