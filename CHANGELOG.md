# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.10.0-rc.0] - Unreleased
### Fixed
- Fix overlapping endpoints detection, it was allowing some corner case overlappings.

## [0.10.0-beta.3] - 2018-12-19
### Changed
- Interface name `device` is reserved now.

### Fixed
- Correctly support Bson.Bin struct.
- False positive overlapping endpoints were detected, EndpointsAutomaton now handles them as valid.
- Correctly serialize triggers on the special "*" interface and device.

## [0.10.0-beta.2] - 2018-10-19
### Added
- Add limit to 64K for string and blobs, 1024 items for arrays.
- Add value validation code for any Astarte type.

## [0.10.0-beta.1] - 2018-08-10
### Added
- First Astarte release.
