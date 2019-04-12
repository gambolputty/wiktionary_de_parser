# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.6.0] - 2019-04-12
### Added
- loading custom methods via `custom_methods` argument in class constructor and `load_methods` function
- Changelog.md (this file)

### Changed
- load all files from `methods` folder and initialize them as extraction methods
- extraction methods must return a `Dict()` now
- `flexion.py`: returns 'genus' and flexion info separately

### Removed
- `method_names` in `__init__.py`

## [0.5.0] - 2019-04-11
### Added
- initial release