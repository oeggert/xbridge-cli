# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [[Unreleased]]

## [0.3.0] - 2023-04-17

### Added

- Optional parameter to `fund` to supply the amount funded
- Optional flag to `bridge build` to fund the locking chain witness accounts

### Changed

- Change the `bridge build` flow to use payments instead of `XChainAccountCreateCommit`s
- In the `bridge build` command, only submit a tx if it hasn't already been submitted
- Accept XRP in the `bridge transfer` command instead of drops
- Adjust default verbosity for `bridge` commands and add `--silent` flags
- Use `-` instead of `_` in all flags and parameters

### Fixed

- Handle long server startup times better

## [0.2.0] - 2023-03-20

### Changed

- Updated to match the latest versions of rippled and the witness server

### Fixed

- Fixed a key algorithm-seed type mismatch for IOU bridge config generation

## [0.1.0] - 2023-02-22

### Added

- Initial release! Please open up an issue in our repo if you have any
  feedback or issues to report.
