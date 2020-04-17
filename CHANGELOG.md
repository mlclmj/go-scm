# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
### Added
- Improve status display text in new bitbucket pull request screen, from [@bradrydzewski](https://github.com/bradrydzewski). See [#27](https://github.com/mlclmj/go-scm/issues/27).
- Implement timestamp value for GitHub push webhooks, from [@bradrydzewski](https://github.com/bradrydzewski).

### Fixed
- Fix issue with GitHub enterprise deep link including API prefix, from [@bradrydzewski](https://github.com/bradrydzewski).

## [1.6.0]
### Added
- Support Head and Base sha for GitHub pull request, from [@bradrydzewski](https://github.com/bradrydzewski).
- Support Before sha for Bitbucket, from [@jkdev81](https://github.com/jkdev81).
- Support for creating GitHub deployment hooks, from [@bradrydzewski](https://github.com/bradrydzewski).
- Endpoint to get organization membership for GitHub, from [@bradrydzewski](https://github.com/bradrydzewski).
- Functions to generate deep links to git resources, from [@bradrydzewski](https://github.com/bradrydzewski).

### Fixed
- Fix issue getting a GitLab commit by ref, from [@bradrydzewski](https://github.com/bradrydzewski).

## [1.5.0]
### Added

- Fix missing sha for Gitea tag hooks, from [@techknowlogick](https://github.com/techknowlogick). See [#22](https://github.com/mlclmj/go-scm/pull/22).
- Support for Gitea webhook signature verification, from [@techknowlogick](https://github.com/techknowlogick).

## [1.4.0]
### Added

- Fix issues base64 decoding GitLab content, from [@bradrydzewski](https://github.com/bradrydzewski).

## [1.3.0]
### Added

- Fix missing avatar in Gitea commit from [@jgeek1011](https://github.com/geek1011).
- Implement GET commit endpoint for Gogs from [@ogarcia](https://github.com/ogarcia).
