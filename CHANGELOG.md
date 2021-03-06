# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a
Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- This CHANGELOG file to track changes to the command line and library APIs.
- Support for custom GHC version, `ghcWithPackages` and `pkgs`

### Changed
- The `snack run` function to accept arguments that will be passed to the built
  executable.
- The `snack.nix` now describes the build environment and packages are
  described through `package.nix` (i.e. to migrate: rename `snack.nix` to
  `package.nix`)

### Fixed
- The module import parsing when the CPP extension is enabled.
- The module import parsing when a BOM is present

[Unreleased]: https://github.com/nmattia/snack/compare/51987daf76cffc31289e6913174dfb46b93df36b...HEAD
