# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.4.3]

### Changed

- Swapped to using `repository` field in `Cargo.toml` (thanks szabgab!)

## [1.4.2]

### Changed

- Updated dependency versions in response to dependabot notices

### Fixed

- Fixed incompatibilities caused by more-recent changes to ratatui and tuirealm

## [1.4.1]

### Added

- Added an error-message display for HTTP client errors

## [1.4.0]

### Added

- Added an option to allow invalid/self-signed certs (thanks, micielski!).

## [1.3.3]

### Changed

- Updated dependency versions in response to dependabot notices.

## [1.3.2]

### Fixed
 - Properly handle server_urls in config that end in a trailing slash

### Added
 - Validation for "is server_url empty?"

## [1.3.1]

### Fixed
 - Updated openssl transitive dependency in Cargo.lock to patch a security hole

## [1.3.0]

### Added
 - Support for toggling "starred" status on a feed entry
 - Support for switching to a "starred entries" view

## [1.2.0]

### Fixed

- Image src URLs will now show up in the list of links in the "read entry" view

## [1.1.0]

### Added 

- Windows config dir support
- `--help` and `--init` command-line flags (`--init` creates an empty config file)


## [1.0.1]

### Fixed

- Github CI 

## [1.0.0]

Initial release
