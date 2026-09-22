# Changelog

All notable changes to Rune Site are documented here, following [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- Initial repository layout.

### Changed

- Sync the ceremony files to skeleton `6374d8fc` through `copier update`: seven dcg packs with fixtures, `.dcg.toml`, the lane table, the direct-push signature check, admin-role rulesets.
- Change the correctness caller to skeleton `5e4657bf`: the controller runs on every same-repository push, draft or ready, so the green draft starts the review round.
- Change the ceremony files to skeleton `60ad8249` through `copier update`: owner-seal and verify-seal messages and nonce, jq guards, versioned display names, `thread-resolver.yaml` retired.
