# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.1.0] - 2024-08-08

### Changed

- Enforces references for whippet dependencies

## [3.0.0] - 2024-06-11

### Changed

- Workflow runs on PHP 8.2

## [2.0.0] - 2023-06-26

### Added

- On PR with change to whippet.lock, comment is added with diff of the compared `whippet deps describe`
- `GH_ACCOUNT_TOKEN` secret must be passed in, a GitHub token with read access to all plugin repos

## [1.0.0] - 2021-10-01

### Added

- Initial release
- Whippet dependencies validate workflow
