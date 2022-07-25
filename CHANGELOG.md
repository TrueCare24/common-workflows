# Changelog

## [Unreleased]
---
### [0.6.0] - 2022-07-25
### Added
* Chart render print when debug

### Changed
* Value files must be placed in `.deploy` directory now
* Renamed default preview value files to `values-dev|stage-preview.yaml`
---
## [0.5.2] - 2022-07-05
### Fixed
* Mapping values files into prereq chart
---
## [0.5.1] - 2022-07-04
### Changed
* The version of the `yq` used has been changed to the `latest`

### Fixed
* `yq` path has been changed to `/usr/local/bin`
---
## [0.5.0] - 2022-07-02
### Changed
* `project_path` variable now scope full project path when converge and dismiss. It's breaking change with v4.
---
## [0.4.1] - 2022-06-27
### Added
* Added [changelog](./CHANGELOG.md)