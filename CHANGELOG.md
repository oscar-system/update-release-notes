# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project tries to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.1 - 2026-04-08

### Added

- [#9](https://github.com/oscar-system/update-release-notes/pull/9) Allow lists starting with `*` in
  addition to `-` when parsing release notes from PR body.

### Changed

- [#10](https://github.com/oscar-system/update-release-notes/pull/10) Print a useful complaint
  instead of garbage when `release notes` section was not found in a PR tagged with `release notes:
  use body`.
- [#12](https://github.com/oscar-system/update-release-notes/pull/12) OSCAR.jl: Fix bug where no PRs
  would show up for patch releases.

## 1.0 - 2026-01-25

Initial release 🎉
