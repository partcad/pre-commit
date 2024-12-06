# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]

## [1.0.0] - 2024-12-01

### Added

- Added `keep-a-changelog` pre-commit hook for CHANGELOG.md updates.
- Added `pre-commit` hook for commit message generation.

## [1.0.1] - 2024-12-01

### Changed

- Updated project description and README.
- Changed contributing documentation to reflect the new project name.
- Adjusted installation guidance.
- Updated example hooks.
- Updated prerequisites and installation instructions.

## [1.1.0] - 2024-12-01

### Changed

- Improved commit message generation.
- Enhanced pre-commit hook functionality.
- Updated documentation for clarity.

### Added

- Added support for configuring the output directory.
- Included instructions for configuring the hook.

### Fixed

- Resolved an issue with hook execution.
- Corrected a typo in the configuration file.

## [1.2.0] - 2024-12-01

### Changed

- Updated pre-commit dependency to v1.1.0.
- Updated example usage and configuration information.
- Enhanced README with additional guides.

### Fixed

- Resolved potential conflict with keep-a-changelog.sh handling.
- Corrected a minor syntax error in the pre-commit configuration.

## [1.3.0] - 2024-12-01

### Changed

- Updated Discord link in CONTRIBUTING.md and README.md.

## [1.4.0] - 2024-12-02

### Changed

- Updated `pre-commit-hooks.yaml` to change the language of `Git Commit AI` and `Changelog AI` hooks to `script`.

## [1.5.0] - 2024-12-02

### Changed

- Added fail_fast flag to Changelog AI hook.

## [1.6.0] - 2024-12-02

### Changed

- Enable passing filenames to commit-msg hook

## [1.7.0] - 2024-12-02

### Fixed

- jq: Argument list too long #3
  - Cleaned up temporary files after API call.

## [1.7.1] - 2024-12-02

### Fixed

- prepare-commit-msg.sh: line 237: /usr/bin/curl: Argument list too long
