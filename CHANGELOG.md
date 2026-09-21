# Changelog

All notable changes to Rune Site are documented here, following [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- Initial repository layout.

### Changed

- Change the correctness caller to skeleton `5e4657bf`: the controller runs on every same-repository push, draft or ready, so the green draft starts the review round.
- Change the ceremony files to skeleton `60ad8249` through `copier update`: owner-seal and verify-seal messages and nonce, jq guards, versioned display names, `thread-resolver.yaml` retired.
