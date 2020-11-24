# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic
Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Support for interval checking with cron scheduled checks

## [0.7.0] - 2020-07-27

### Added
- Special case handling for keepalive checks
- Test cases for zero interval

### Changed
- Reformatted and cleaned up README
- Added information on non-repeating alerts to README

## [0.6.2] - 2020-05-10

### Changed
- Updated parameter call for defaults, Otto doesn't support assigning default values in function definition

## [0.6.1] - 2020-05-08

### Changed
- Fixed releast to use all github actions, no included scripts

## [0.6.0] - 2020-05-08

### Changed
- Added default occurrences and interval as parameters to allow override(s)
- Reorganized README, added above and switched examples to yaml

## [0.5.0] - 2020-02-19

### Changed
- Minor github upload script changes
- Use bracket accessor syntax for annotations (@flowerysong)

## [0.4.0] - 2020-02-10

### Changed
- Migrated from Travis CI to GitHub Actions

## [0.3.2] - 2019-12-03

### Changed
- Reformatted README for [Plugin Style Guide](https://github.com/sensu-plugins/community/blob/master/PLUGIN_STYLEGUIDE.md)

### Added
- Testing with Karma
- Build and release scripts

### Removed
- Janky test script lib/fatigue_check_test.js

## [0.3.1] - 2019-12-03

### Changed
- Fixed is_resolution checking

## [0.3.0] - 2019-11-27

### Added
- Support for entity annotations

## [0.2.2] - 2019-09-21

### Changed
- README updated to include sensuctl asset add for bonsai

## [0.2.1] - 2019-09-04

### Changed
- README fixed for syntax error, forced version update to refresh bonsai

## [0.2.0] - 2019-08-30

### Changed
- Rounding the interval/check interval up just in case it's not a multiple

## [0.1.3] - 2019-06-18

### Changed
- More README fixes for clarity, forced version update to refresh bonsai

## [0.1.2] - 2019-06-18

### Changed
- Fixed README for Bonsai

## [0.1.0] - 2019-06-18

### Changed
- Updated to use occurrences_watermark

### Added
- Suppression of flapping events

