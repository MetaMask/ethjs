# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.5.0]
### Uncategorized
- deprecate nodejs <8.17, npm<6
- chore: format CHANGELOG.md
- rename package from ethjs to @metamask/ethjs
- chore: add .nvmrc set to v12
- add package publishConfig
- npm v5+ compat: rename prepublish script to prepare
- devDeps: cross-env@1.0.7->6.0.3
- devDeps: remove legacy check-es3-syntax-cli
- devDeps/test: ethereumjs-testrpc->ganache-cli
- devDeps: update web3@0.17.0-beta -> 0.20.7
- remove coveralls,travis. npm [test-travis,coveralls]->test:coverage
- build dist
- chore: refresh package-lock.json
- ci: Remove Travis integration
- ci: Add GitHub Actions workflows

## [0.3.5]
### Fixed
- Fix getTransactionSuccess unhandled promise rejection
- Fix getTx unhandled promise rejection

## [0.3.4]
### Fixed
- EthJS-RPC
  - Fix RPC unhandled promise rejection.

## [0.2.8]
### Added
- getTransactionSuccess
  - Added the very essential getTransactionSuccess method

## [0.2.7]
### Changed
- abi updated, format and contract updates
  - Updated ethjs-abi, ethjs-format, ethjs-query, ethjs-contract
  - The updates will fix some small problems with geth/parity compat

## [0.2.6]
### Added
- added abi, personal sign/ecrecover
  - Expose ABI module
  - Added personal_sign/personal_ecRecover
  - Added log decoders

## [0.2.4]
### Changed
- package updates
  - Updates provider, handle 405 better

## [0.2.0]
### Changed
- provider upate
  - Set Provider now more dynamic accross all modules

## [0.1.9]
### Fixed
- Specified more dependencies in package.json

## [0.1.6]
### Changed
- handle 500 errors better
- Update ethjs-query

## [0.1.5]
### Changed
- update unit formatting

## [0.1.4]
### Fixed
- BN formatting fix

## [0.1.3]
### Changed
- upgrade ethjs-query

## [0.1.1]
### Added
- ethjs
  - Basic testing
  - Basic docs
  - License

[Unreleased]: https://github.com/MetaMask/ethjs/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/MetaMask/ethjs/compare/v0.3.5...v0.5.0
[0.3.5]: https://github.com/MetaMask/ethjs/compare/v0.3.4...v0.3.5
[0.3.4]: https://github.com/MetaMask/ethjs/compare/v0.2.8...v0.3.4
[0.2.8]: https://github.com/MetaMask/ethjs/compare/v0.2.7...v0.2.8
[0.2.7]: https://github.com/MetaMask/ethjs/compare/v0.2.6...v0.2.7
[0.2.6]: https://github.com/MetaMask/ethjs/compare/v0.2.4...v0.2.6
[0.2.4]: https://github.com/MetaMask/ethjs/compare/v0.2.0...v0.2.4
[0.2.0]: https://github.com/MetaMask/ethjs/compare/v0.1.9...v0.2.0
[0.1.9]: https://github.com/MetaMask/ethjs/compare/v0.1.6...v0.1.9
[0.1.6]: https://github.com/MetaMask/ethjs/compare/v0.1.5...v0.1.6
[0.1.5]: https://github.com/MetaMask/ethjs/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/MetaMask/ethjs/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/MetaMask/ethjs/compare/v0.1.1...v0.1.3
[0.1.1]: https://github.com/MetaMask/ethjs/releases/tag/v0.1.1
